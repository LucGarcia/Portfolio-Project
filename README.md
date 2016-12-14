Overview
--------

The Portfolio Project is my second project in the Udacity Full Stack Web Developer Nanodegree.

In it I replicated a [design mockup](https://storage.googleapis.com/supplemental_media/udacityu/2655898586/design-mockup-portfolio.pdf) that was provided as a PDF file in html and CSS, creating a responsive website that displays images and text and is functional across different devices.

Tools
-----

I used [Bootstrap](http://getbootstrap.com) as a framework and improved responsiveness and performance using media queries as well as srcset and sizes attributes in the images.
Also, images were processed with [Grunt](http://gruntjs.com/) integrating [ImageMagick](http://www.imagemagick.org/script/index.php) and [ImageOptim](https://imageoptim.com) in order to reduce size and create different images that can be displayed at different viewport widths.

Design choices
--------------

The grid layout respects the original design when viewed in desktops and tablets. For smaller mobile devices a decision was made to change the layout so that each app in the "featured works" section is displayed at around 80% of the viewport. In this way, scrolling down to view content is easier.
