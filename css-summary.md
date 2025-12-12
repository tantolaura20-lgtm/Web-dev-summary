1. What Is CSS & How It Works

What i learned:
CSS (Cascading Style Sheets) is the language used to style HTML elements like colors, layout, fonts, spacing, and more

Example:
body {
  background-color: lightblue;
}
h1 {
  color: white;
  text-align: center;
}

2. CSS Syntax

What i learned:
CSS rules consist of selectors and declarations. Selectors point to HTML elements; declarations (inside {}) define property–value style pairs.

Example:
p {
  color: red;
  font-size: 18px;
}


3. Selectors (Targeting Elements)

What i learned:
Selectors choose which HTML elements to style. You’ll use basic selectors like element, class, and ID, as well as others like attribute, pseudo-class, and pseudo-element selectors.

Examples:

/* Element selector */
h2 { color: blue; }

/* Class selector */
.highlight { background: yellow; }

/* ID selector */
#main-title { font-size: 2rem; }


4. Colors & Text Styling

What i learned:
i can control text color, alignment, decoration, transformation (uppercase/lowercase), and spacing.

Example:

p {
  color: #333;
  text-align: justify;
  text-decoration: underline;
  text-transform: uppercase;
}


5. Backgrounds

What i learned:
CSS can add background colors, images, and control how backgrounds repeat or attach.

Example:

body {
  background-image: url('bg.png');
  background-repeat: no-repeat;
  background-size: cover;
}


6. The Box Model (Margin, Border, Padding)

What  learned:
Every HTML element is a box. CSS lets you control its spacing: margin (outside space), padding (inside space), and border.

Example:

div.box {
  margin: 20px;
  padding: 15px;
  border: 2px solid black;
}


7. Fonts

What i learned:
i can specify font family, size, weight, and style for text.

Example:

body {
  font-family: Arial, sans-serif;
  font-size: 16px;
  font-style: italic;
}


8. Links

What i learned:
CSS can style links differently depending on their state (normal, hover, visited).

Example:

a {
  color: blue;
  text-decoration: none;
}
a:hover {
  color: red;
}


9. Lists & Tables

What i learned:
You can style lists (e.g., remove bullets, add custom markers) and tables (borders, spacing, alignment) with CSS.

Examples:

ul { list-style-type: none; }
table { border-collapse: collapse; }
td { border: 1px solid #888; }


10. Positioning

What i learned:
Control where elements appear using position: static, relative, absolute, fixed, and sticky.

Example:

div.fixed {
  position: fixed;
  bottom: 10px;
  right: 10px;
}



11. Flexbox (Responsive Layouts)

What you learn:
Flexbox makes it easy to build flexible, adaptive layouts. You use properties like display: flex, flex-direction, justify-content, and align-items.

Example:

.container {
  display: flex;
  justify-content: center;
  align-items: center;
}


12. Responsive Web Design & Media Queries

What i learned:
Media queries let you apply different styles depending on screen size or device type — key for responsive design.

Example:

/* For screens wider than 600px */
@media (min-width: 600px) {
  body { font-size: 18px; }
}
