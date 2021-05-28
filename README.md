
# layout-markup
This repository contains the markup for popsockets content assets.

[banner-carousel](https://github.com/PopSockets/layout-markup/blob/main/content-assets/banner-carousel.html)  
[banner-carousel-full-width](https://github.com/PopSockets/layout-markup/blob/main/content-assets/banner-carousel-full-width.html)  
[banner-image](https://github.com/PopSockets/layout-markup/blob/main/content-assets/banner-image.html)  
[banner-image-full-width](https://github.com/PopSockets/layout-markup/blob/main/content-assets/banner-image-full-width.html)  
[banner-video](https://github.com/PopSockets/layout-markup/blob/main/content-assets/banner-video.html)  
[banner-video-full-width](https://github.com/PopSockets/layout-markup/blob/main/content-assets/banner-video-full-width.html)  
[card-deck-2](https://github.com/PopSockets/layout-markup/blob/main/content-assets/card-deck-2.html)  
[card-deck-3](https://github.com/PopSockets/layout-markup/blob/main/content-assets/card-deck-3.html)  
[card-deck-4](https://github.com/PopSockets/layout-markup/blob/main/content-assets/card-deck-4.html)  
[split-banner-carousel-text](https://github.com/PopSockets/layout-markup/blob/main/content-assets/split-banner-carousel-text.html)  
[split-banner-text-image](https://github.com/PopSockets/layout-markup/blob/main/content-assets/split-banner-text-image.html)  

## layout styles
Certain classes can be applied to the banner to change positioning and text colors. Simply add the following classes to any div that contains the `banner` class to apply the desired styles.

### Text Color
    text-dark
    text-light

### CTA positioning

    text-top-left
    text-top-middle
    text-top-right
    text-middle-right
    text-bottom-right
    text-bottom-middle
    text-bottom-left
    text-middle-left
    text-middle-middle

Example: 

    <div class="banner banner-image banner-full-width text-dark text-bottom-left">
        <a href="https://popsockets.com/popmounts?lang=en_US">
            <picture>
                <source media="(max-width: 768px)"
                    srcset="https://via.placeholder.com/720x960" />
                <source media="(min-width: 769px)"
                    srcset="https://via.placeholder.com/1130x636" />
                <img alt="Image alt text" class="lazyload"
                    src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw=="
                    data-src="https://via.placeholder.com/1130x636"
                    style="width: 100%" />
            </picture>
        </a>
        <div class="container">
            <div class="card-img-overlay text-overlay ">
                <a class="home-main-overlay" href="https://popsockets.com/popmounts?lang=en_US">
                    <h1><span id="home-main-top-text">Header</span></h1>
                    <h4>Sub header</h4>
                    <btn class="btn btn-primary">Button Text</btn>
                </a>
            </div>
        </div>
    </div>
