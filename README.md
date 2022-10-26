# Typography CSS library
**Author:** *First Lastname*
## Demo site
Link to **[demo](http://www.github.io)** site for preview.
## Description
The library acts as a predefined point that you can quickly and easily use on your website. Using codes and tags, everything is connected.
## Navigation
1. [Implementation](#Implementation)
2. [Usage](#Usage)
3. [Components](#Components)
   1. [Colours](#Colours)
   2. [Body](#Body)
   3. [Navigation bar](#Navigation-bar)
   4. [Headings](#Headings)
   5. [Text](#Text)
   6. [Lists](#Lists)
   8. [Alert](#Alert)
   9. [Pictures and gallery](#Pictures-and-gallery)
   10. [Code showcase](#Code-showcase)
## Implementation
Download style.css file at **[docs/](https://github.com/pslib-cz/2022l4web-css-typographic-library-Anitramis.git)** folder and implement it into your site by connecting it with your HTML code in the `<head>` part

## Usage
Presets for your website, defined design, bullet point and photos.

## Components

### Colours
Selector :root defines colours for normal website mode.

### Body
The whole body of your HTML code has predefined `font-family`. 

### Navigation bar
Navigation bar is made using tag `<ul>` and tag `<a>`. Easy scroll for content.

### Headings
Tag `<h>` is defined directly.

### Text
etx is defined using a tag `<p>`. 

### Lists
Tag `<li>` is defined directly, for complicated list.

### Alert
Nice and easy looked alert for website. Complete defined.

### Pictures and gallery
Tag `<img>` in `<figure class="photo_alone">` for giving a moving picture in galery.

### Code showcase
Here is short showcase of HTML code:

<section class="section_s" id="Photo">
        <h2 class="main_section">Photo</h2>
        <p>The approximate image, using the above definition, can look like this. [in HTML use class - .photo_alone]
        </p>
        <div class="boxes">
            <div class="flex">
                <p><b>.photo_alone</b> {<br>
                    overflow: hidden;<br>
                    width: fit-content;<br>
                }
                <br>
                <b>.photo_alone a:hover img</b> {<br>
                    transform: scale(1.07);<br>
                    transition: 0.3s;<br>
                }</p>
            </div>
            <p class="character">&#9758;</p>
            <div class="flex_non">
                <figure class="photo_alone">
                    <a href="./img/goat.jpg">
                        <img src="./photo/forest-ge3559edf6_640.jpg" alt="forest">
                    </a>
                </figure>
            </div>

Thanks for reading...