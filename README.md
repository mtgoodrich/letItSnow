# letItSnow
Let It Snow Custom jQuery Plugin
Random image sizes, random image speed, random image opacity for a feeling of depth.

Add all the files to your main directory, if you nest files in other folders, be sure to change the path to that image/stylesheet/javascript file.
If you move/change the images directory, update the path in '$imgSrc' inside the jquery.letItSnow.js file.

Best results are achieved if a parent element (body, section, div with id) has a defined width and height (300+) as well as a dark background, unless you change the images to darker images.
Load this after jQuery loads on the page, either in a js file or on the page where you want the snowflakes to show.
    <script>
        $(document).ready(function(){
            $('header > div').letItSnow({
                numSnowflakes : 20 // number of snowflakes per cycle
            });
        });
    </script>


You can replace any or all of the images with other images (cats, dogs, stars, etc.) for a different effect.

The default number of snowflakes(images) per cycle is 5, but if you want more, or less, add that as a value in the object when calling the letItSnow script.

MIT License: Use this, add to it, update it, change it a bit to your liking, but attribute proper credit for ideation or inspiration where due.

Troubleshooting:
If the snowflakes aren't showing up and you've copy pasted everything properly, check that the parent element of the selector you chose has a height and width specified.
Check that the js files are loaded at the bottom of the page.
If the animation works, but the images aren't showing, check that the snowflake images have a width and height specified. If not, is there any page level css overridding their size?

Good luck, have fun, enjoy.


