## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

### Lighthouse Tests

### Initial Test
### Desktop: no throttle
![Test 1: Desktop no throttle](https://github.com/DavidHoffman80/frontend-nanodegree-mobile-portfolio/blob/master/WebsiteOptimizationScreenshots/Test1-Desktop-noThrottle.png)

### Mobile: Applied 3G throttle
![Test 1: Mobile applied 3G throttle](https://github.com/DavidHoffman80/frontend-nanodegree-mobile-portfolio/blob/master/WebsiteOptimizationScreenshots/Test1-Mobile-Applied3GThrottle.png)

### Final Test
### Desktop: no throttle
![Final Test: Desktop no throttle](https://github.com/DavidHoffman80/frontend-nanodegree-mobile-portfolio/blob/master/WebsiteOptimizationScreenshots/Test6-Desktop-noThrottle.png)

### Mobile: Applied 3G throttle
![Final Test: Mobile applied 3G throttle](https://github.com/DavidHoffman80/frontend-nanodegree-mobile-portfolio/blob/master/WebsiteOptimizationScreenshots/Test6-Mobile-Applied3GThrottle.png)

### Conclusion
By doing a little restructuring I was able to acheive a 100 in Google's Lighthouse tests for both desktop and mobile versions. I was able to take an initial desktop test of "Time to Interactive" from 200ms to 110ms, "First Meaningful Paint" from 270ms to 110ms. In the mobile version I was able to take "Time to Interactive" from 2490ms to 2020ms, "First Meaningful Paint" from 2490ms to 1340ms.