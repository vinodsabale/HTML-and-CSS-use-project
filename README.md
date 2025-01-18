# HTML-and-CSS-use-project
Language  Are use HTML,CSS,JS.

HTML (index.html):

A webpage titled "Update CSS."
Contains a container with controls for:
Adjusting spacing (range: 10–200).
Adjusting blur (range: 0–25).
Selecting a base color using a color picker.
Includes an image from an external Unsplash URL.
Links to an external CSS file (style.css) and a JavaScript file (app.js).
CSS (style.css):

Uses CSS variables:
--base: Default background color (#ffc600).
--spacing: Default padding (10px).
--blur: Default blur effect (2px).
Styles the container with:
Centered text alignment.
Sans-serif font.
Font size of 20px.
20px margin.
The image is styled with:
Dynamic padding, background, and blur using CSS variables.
Fixed width of 100vh.
Input fields have:
Transparent background.
No borders.
Width of 100px.
JavaScript (app.js):

Selects all input elements within the controls container.
Updates CSS variables dynamically when the user changes an input.
Adds "px" to spacing and blur values while leaving color values unchanged.
Allows real-time updates to spacing, blur, and base color on the webpage.
