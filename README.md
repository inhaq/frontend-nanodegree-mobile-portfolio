## Website Performance Optimization portfolio project

In this project, I have optimize online portfolio for performance! In particular, optimize the CRP and make page render as fast as possible.

Open index.html to launch this project.

[Live Demo](http://inzi.me/frontend-nanodegree-mobile-portfolio/)

### Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html

- Shift analytics code to the bottom index.html
- Did inline styles
- Google font optimisal approach
- Add media for print query
- Compressed/Convert-to-base64 and resized image
- Load scripts asynchronously

#### Part 2: Optimize Frames per Second in pizza.html

- DOM element selectors getElementsbyClassName
- Removed unwanted calculation from the ChangePizzaSizes loop
- Removed determineDx function and optimised calculation
- Moved repeated calculation outside of the loop in updatePositions function
- Added a scroll function to use the requestAnimationFrame API to optimize concurrent animations
- Moved variable initialization before loop to improve performance
- Calculate number of pizzas that should be displayed on screen dynamically


### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html">The fewer the downloads, the better</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html">Reduce the size of text</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html">Optimize images</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html">HTTP caching</a>

### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>
