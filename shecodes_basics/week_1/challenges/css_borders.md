# CSS Borders Challenge

CSS borders enhance the appearance of elements by adding visual outlines, depth, and separation. When combined with border-radius and box-shadow, they contribute to a modern, polished UI.
Border: this is the third layer element you can add to your HTML elements.
Borders sit between the padding and the margin.
For this challenge, I focused on enhancing the appearance of a button by giving it a border, rounded corners, and a subtle shadow to create a card-like, clickable effect.

## Overview of the Code

In css_borders_challenge.html, I followed the layout demonstrated in this CodePen: https://codepen.io/matthieua/full/EBeOqe?editors=1100.

I:

- Styled the “Apply now” button with a 1px solid border in purple.
- Rounded the button’s edges using border-radius: 50px for a soft pill shape.
- Added box-shadow to create depth and a slight 3D appearance.
- Maintained button spacing and alignment with margin: 20px auto.
  This challenge helped me understand how borders, radius, and shadows can elevate basic elements into visually engaging, clickable components.

For example in this css code
button {
border: 1px solid #885df1;
}
First value is the thickness

Second is the style (none | hidden | dotted | dashed | solid | double | groove | ridge | inset | outset)

Third is the color

The border-radius CSS property rounds the corners of an element's outer border edge, it's aplication is same as that of a margin.

### For a shadow

button {
box-shadow: 10px 5px 5px red;
}

Explained in this manner: box-shadow: horizontal-offset vertical-offset blur-radius color;
1st value (10px): How far the shadow moves left/right
2nd value (5px): How far the shadow moves up/down
3rd value (5px): How much the shadow blurs
4th value (red): Shadow color
You can optionally add a spread radius (4th numeric value) or use the inset keyword for inner shadows too.

#### Full Shadow Example

html
<button style="box-shadow: 10px 5px 15px rgba(0, 0, 0, 0.3);">
Stylish Shadow
</button>
or
CSS
button {
box-shadow: 10px 5px 15px rgba(0, 0, 0, 0.3);
}

10px: shadow goes right
5px: shadow goes down
15px: blur
rgba(0,0,0,0.3): soft black color

## Relevance to Healthcare

Visual design is important in healthcare applications — especially when drawing attention to call-to-action elements like “Book Appointment” or “Submit Form.” Styling buttons with borders and shadows makes them more visible, accessible, and intuitive for users, especially in high-stakes environments.

This challenge is part of my SheCodes Basics journey and strengthens my skills in creating visually responsive components that improve user experience.
