## Website Performance Optimization portfolio project
<!--You need to write a personalised README that lists the optimisations you performed to meet specifications for Critical Rendering Path, Frame Rate, and Computation Efficiency. Likewise, the README should also mention all the steps to successfully run the application.-->

### Steps taken to optimize the portfolio

- Reduced the number of sliding pizzas from 200 to less than 40. This is to avoid creating extra data that the user will not even see and gives website visitors a better FPS experience.

- scrollTop was moved to the outside of the for loop because it doesn't need to be calculated more than once.

- Optimized all the images using ImageOptim, resized some of them as well as they were too large

- Removed unnessesary white space

- Added a media query to print.css

### Access

- To access the portfolio, download or clone the file onto your local computer. If the folder is zipped, unzip the folder and open the index.html file in your browser. You will now be able to access the portfolio.
