# Multiple-Infinite-Image-Loop

![Multiple-Infinite-Image-Loop](https://media.giphy.com/media/jf8AC2AI9r9vgBL0z0/giphy.gif)

## About The Project

A little CSS and JavaScript project providing a modification of the work produced
by [Jack Babb](https://codepen.io/zendergo2/pen/VjQpOo) to allow for multiple infinite image loops to appear on a single
webpage.

## Usage (Quickstart)

1. Add [`InfiniteSlider.css`](InfiniteSlider.css) and [`InfiniteSlider.js`](InfiniteSlider.js) to your project
   directory.
2. Link CSS file to your site's webpage before the `</head>` tag:
```html
<link rel="stylesheet" href="InfiniteSlider.css">
```
3. Link JavaScript file to the same webpage before the `</body>` tag:
```html
<script src="InfiniteSlider.js"></script>
```
4. Add and modify as desired the required scroller(s) within the `<body>`:
```html
<div class="slider-container">
    <div class="slider">
        <span><img src="http://placehold.it/400x400" alt="400x400"/></span>
        <span><img src="http://placehold.it/400x350" alt="400x350"/></span>
        <span><img src="http://placehold.it/400x300" alt="400x300"/></span>
        <span><img src="http://placehold.it/400x250" alt="400x250"/></span>
        <span><img src="http://placehold.it/400x200" alt="400x200"/></span>
        <span><img src="http://placehold.it/400x150" alt="400x150"/></span>
        <span><img src="http://placehold.it/400x100" alt="400x100"/></span>
        <span><img src="http://placehold.it/400x50" alt="400x50"/></span>
    </div>
</div>
```
5. For more advance control (e.g. changing slider speeds and design) adjust settings as necessary within
   both [`InfiniteSlider.css`](InfiniteSlider.css) and [`InfiniteSlider.js`](InfiniteSlider.js).
6. See [demo](Demo.html) for a working example.

## Contributions

All and any improvements, features and modifications are graciously appreciated.

## License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for more information.

## Acknowledgements

Inspiration and Modification:

* [Jack Babb - @zendergo2](https://codepen.io/zendergo2/pen/VjQpOo)
* [Chris Coyier - @chriscoyier](https://css-tricks.com/infinite-all-css-scrolling-slideshow/)
