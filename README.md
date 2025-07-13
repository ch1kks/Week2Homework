# TASK 🚧

Create a Kazimir Malevich's ([Example](https://artsandculture.google.com/asset/stroyuschiysya-dom-house-under-construction-kasimir-malevich/cAH5v2Pqbdb2GQ?hl=en)) inspired artwork using just HTML/CSS. No image.
You must use a separated stylesheet file. Some elements that requires you to do your research and exploration at home:

1. Utilize both `position: absolute;` & `position: relative;` in your work
2. Experiment with [CSS display property](https://www.w3schools.com/cssref/pr_class_display.asp).
3. Experiment with [CSS z-index property](https://www.w3schools.com/cssref/pr_pos_z-index.asp) to organize element's order.
4. Experiment with [CSS transform property](https://www.w3schools.com/cssref/css3_pr_transform.asp) to rotate and transform your elements.

# TUTORIAL ✏️

## CSS `display` Property
Every HTML element on a web page is treated a rectangular box. The display property in CSS determines just how that rectangular box behaves.

### Common Uses
`display: block` is the default of elements like `<div>`, `<p>`, `<section>`, etc. Make an element start on a new line and take up the full width available. Can assign `width` & `height`. _Tip:_ You would use it when you want elements to take up the full width of their container and appear on separate lines, like paragraphs, headings, or sections.

`display: inline` is the default of elements like `<span>`, `<em>`, etc. Wrapping text in inline elements within a string of text doesn’t break the flow of the text. Cannot assign `width` & `height`. _Tip:_ It is handy when you want elements to appear next to each other on the same line, such as links within a paragraph or a series of small icons.

`display: inline-block` is the hybrid that functions like `display: inline`, but you can assign `width` & `height`. _Tip:_  It's commonly used for creating navigation menus or arranging images horizontally.

`display: none` completely hides an element, making it disappear from the webpage. Use this when you want to hide an element, like a dropdown menu that appears only when triggered.

**Link:** [https://www.w3schools.com/cssref/pr_class_display.php](https://www.w3schools.com/cssref/pr_class_display.php)

## CSS `z-index` Property 
The z-index property in CSS determines the stacking order of positioned elements, allowing you to control which elements appear in front of or behind others on the z-axis.
![basicz-index](https://cdn.glitch.global/d3979269-4cf7-41ce-9f4c-1ef0b45f95b1/z-index.png?v=1719658349685)

### Tip
In addition to typical numeric usage for arrangement. You can use `z-index: -1;` or `z-index: 10000;` to ensure an element is positioned behind everything else or to bring it to the very front, respectively.

**Link:** [https://www.w3schools.com/cssref/pr_pos_z-index.php](https://www.w3schools.com/cssref/pr_pos_z-index.php)

## CSS `transform` Property 
The transform property in CSS allows you to apply various visual transformations to an element, such as rotating, scaling, skewing, or translating (moving) it, enabling you to manipulate and animate elements in creative ways without changing the underlying structure of the document.

**Link:** [https://www.w3schools.com/cssref/css3_pr_transform.php](https://www.w3schools.com/cssref/css3_pr_transform.php)

**Complete Guide:** [https://www.freecodecamp.org/news/complete-guide-to-css-transform-functions-and-properties/](https://www.freecodecamp.org/news/complete-guide-to-css-transform-functions-and-properties/)

