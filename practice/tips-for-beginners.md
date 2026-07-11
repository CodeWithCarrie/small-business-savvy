# HELPFUL TIPS FOR BEGINNERS

## FORMATTING YOUR CODE

Just like with JavaScript, it is important to use indenting with HTML and CSS to keep your code organized and represent nested sections and tag groups.

## CSS PROPERTIES

There are a lot of CSS properties out there, and some will work for one HTML tag but not another. It takes a while to learn what's what. I recommend that you start with [the most common ones](https://www.makeschool.com/academy/track/web-dev-with-node/your-first-website--landing-page/css-properties), but a comprehensive list can be found at [W3Schools](https://www.w3schools.com/cssref/). To adjust your CSS, use the browser's Inspect Elements feature to get specifications and see visualizations of your margins, paddings, sizes, etc.

## COLOR CODES

You can define colors multiple ways. `"red"`, `"#FF0000"`, and `"RGB(100,0,0)"` all mean the same thing. VS Code has a built-in color picker if you hover over the name/code in your CSS file.
See [this resource](https://htmlcolorcodes.com/) for more information. There is a limited list of colors that have simple names like "red" - click on the link further down on that page to get the full list.

## VALUES FOR HEIGHT AND WIDTH

There are different ways to define these. Sometimes you want to make something relative to the browser view pane with a value like `100vw` (the entire width of the screen) or `20vh` (20% of the view height). Other times you want to take a percentage that is relative to the height of the `<div>` that the content is within - `60%`, for example. And sometimes you want to have a fixed constraint like `200px` (pixels). You can also base things on text height with something like `1.3rem` (130% the height of the default text for the entire page) or `0.9em` (90% of the height of the nested text, like if it's been defined within a `<p>` or `<div>`).

Here's a [good resource with examples](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Sizing_items_in_CSS).

## LINKING TO IMAGES FROM GOOGLE DRIVE

In cases where I have my own images saved on my Google Drive, I am able to use them by grabbing the specific id and forming the url like this: `https://drive.google.com/thumbnail?id=xyz&w=1000`. (Note: The `w` parameter represents the width of the image you want to import in pixels. Make it larger than you need but not too large or it will take longer to load on the page.)
