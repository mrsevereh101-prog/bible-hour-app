# Tools

`art-reading-station.html` is the current home picture (the reading station). `art-scene.html` is the earlier one. Each is a three.js scene (three@0.160.0) that renders the home screen picture
(bread basket, oil lamp, glass cup of wine, open book). To re-render it: `npm i three@0.160.0`
next to the file, serve the folder over http, open the page in headless Chromium at 1200x1000,
take a screenshot, resize it to 1020x850 WebP, and embed it as base64 in the `<img class="artsvg">`
tag of `index.html`.
