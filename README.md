Cameron Pittman: Portfolio Website Optimization
===============================================

Goal
----
The PageSpeed score of 90 is for index.html (both mobile and laptop scores should be at least 90).

The frame rate of 60fps should be obtained for the pizza page (views/pizza.html). The file you need to study and change is views/js/main.js.

The original project is available at <a href="https://github.com/udacity/frontend-nanodegree-mobile-portfolio">https://github.com/udacity/frontend-nanodegree-mobile-portfolio</a>.

Optimizations
=============

Images
------
- Resolution was reduced when unnecessarily large
- All images are now hosted locally

JavaScript
----------
- Scripts not critical to build the DOM are loaded asynchronously
- Moved non-critical scripts to bottom of html

CSS
---
- CSS for print taken out of the critical rendering path
- stylsheet minimized and loaded inline

Fonts
-----
- Fonts are loaded with @font-face vs link rel


Pizza page spicific FPS optimizations
=====================================

- Reduced Images
- Removed style css file and put it as inline stylesheet
- Moved js to bottom of html

