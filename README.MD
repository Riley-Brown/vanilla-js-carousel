<h1 style="text-align: center; color: #333">Fullscreen reusable vanilla JS carousel for images and videos</h1>

<h5 style="text-align: center; margin-bottom: 20px; color: #333">Built using HTML5 data attributes </h5>

![alt text](https://i.imgur.com/OOOcuJ8.gif "video")

# Usage:

Simply download the `carousel.js` file in this repo and include it at the bottom of your HTML.

Also download the `carousel.css` file for the carousel styling and include it in the head of your HTML.

I included an `index.html` that can be used as a reference on how to use the HTML properly, as well as the code below.

```html
<div class="carousel" data-carousel="1" data-speed="1000">
  <span class="carousel-control-left"></span>
  <span class="carousel-control-right"></span>
  <div class="carousel-content">
    <!-- add extra last pic first and extra first pic last for hover effect to work properly  -->
    <img src="img/img-5.jpg" alt="" />
    <img src="img/img-1.jpg" alt="" />
    <img src="img/img-2.jpg" alt="" />
    <img src="img/img-3.jpg" alt="" />
    <img src="img/img-4.jpg" alt="" />
    <img src="img/img-5.jpg" alt="" />
    <img src="img/img-1.jpg" alt="" />
  </div>
</div>
```

- Each carousel must contain the `.carousel` class and a `data-carousel` attribute and `data-speed` attribute

- All images or videos must go in the `.carousel-content` class

- You can have multiple carousels on the same page, each with different speeds. Make sure to have unique `data-carousel` values for multiple carousels on one page
- The `data-speed` attribute controls the speed in miliseconds for each carousel
- For the hover effect in this carousel to work properly, I recommend to place an extra last image first, as well an extra first image last

Most of the styles are on the `.carousel-content` class that you can easily overwrite if you need. Images display 100vh on mobile which can be changed with a media query.
