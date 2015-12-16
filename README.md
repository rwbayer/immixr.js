# immixr.js
an easy instagram collage for your website

Check out the [immixr 2.0 homepage](http://www.immixr.me) for examples and more information.

## Installation Instructions

1. Download immixr.js (clone this repo)
2. Put immixr.js in the javascript folder of your website.
3. Put immixr.css in the css/style folder of your website.
4. Include both in your html file.
5. In your main.js, a new javascript file, or in your html in script tags, initialize immixr.
   ```javascript
   $(document).ready(function() {
			var userID = "YOUR_USER_ID";
			var accessToken = "YOUR_ACCESS_TOKEN";
			var biggestWidth = BIGGEST_IMAGE_WIDTH;
			var opacity = IMAGE_OPACITY;
			var gutterWidth = GUTTER_WIDTH;

			immixr(gutterWidth, opacity, userID, accessToken, biggestWidth);
		});
   ```
6. Add `<div id="immixr"></div>` to your html. immixr expands to fit its parent div. Its parent div needs to have `position: relative;` and a set height.
7. Send me a picture of immixr in action! (or what went wrong along the way)

## More Info
Check out the [immixr 2.0 homepage](http://www.immixr.me) for examples and more information.

If you find an issue or have a suggestion, use the [issues page]().

If you'd like to contribute, create a [pull request]() or [tweet me](https://twitter.com/rwbayer).

