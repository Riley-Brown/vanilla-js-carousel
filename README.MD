<h1 style="text-align: center; color: #333">Fullscreen reusable vanilla JS carousel for images and videos</h1>

<h5 style="text-align: center; margin-bottom: 20px; color: #333">Built using HTML5 data attributes </h5>

![alt text](https://i.imgur.com/wtfkz4o.gif "video")

#Usage:

Simply download the `carousel.js` file in this repo and include it at the bottom of your HTML.

Also download the `carousel.css` file for the carousel styling and include it in the head of your HTML.

I included an `index.html` that can be used as a reference on how to use the HTML properly.

```
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
