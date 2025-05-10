# CSS Positioning Challenge

CSS positioning is the technique used to place elements (like images or text) within a webpage in a structured, visually appealing manner. It allows designers to align, center, or layer content based on how it should appear in different screen sizes or layouts.

There are several positioning methods in CSS, but for this challenge, I used block display and margin auto to center content.

For this challenge, I utilized Internal CSS, meaning the styles were written directly inside the HTML document using the <style> tag.

## Overview of the Code

In css_positioning_challenge.html, I followed the layout demonstrated in this CodePen: https://codepen.io/matthieua/full/XLPByE?editors=1100.

I:

- Centered the main image horizontally on the page using display: block and margin: 0 auto.
- Centered the text "More info" using a <p> tag with text-align: center.
- Maintained a clean and accessible layout using semantic tags.
- Applied light background color for visual comfort.

This exercise helped me understand how to position elements in CSS using basic but powerful layout rules.

### Understanding Inline vs Block Elements in Positioning

By default, every HTML element behaves as either a block-level element or an inline element.

Block elements (e.g., <div>, <p>, <h1>) start on a new line and stretch to fill the width of their container. They respond to properties like width, height, margin, and padding.

Inline elements (e.g., <span>, <a>, <strong>) appear within lines of text and do not support width, height, or vertical margins by default.

### Why This Matters:

Before applying positioning styles like margin: auto or text-align: center, it's important to know an element's default display behavior.

This helps you decide whether to:

- Convert an inline element to block using display: block;, or
- Wrap it inside a block-level container for styling to take effect.

Example Fix:
html
`<strong class="centered-text">More Info</strong>`

css
.centered-text {
display: block;
text-align: center;
}
Without display: block, the centering wouldn't work — because <strong> is inline by default.

## Relevance to Healthcare

In healthcare interfaces, proper positioning of elements like images, buttons, and critical information (e.g., emergency instructions or test results) improves clarity and user experience. Centered content draws attention and enhances accessibility for patients and health workers navigating digital tools.

This is part of my SheCodes Basics journey and provided hands-on experience in aligning and styling content for real-world application in web design — especially in fields like digital health.
