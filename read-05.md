#  CSS properties images, color and Text 

![cssp](https://cdn.educba.com/academy/wp-content/uploads/2019/08/CSS-Text-Formatting-Properties2.png)

**Images**

*Images can improve the design and the appearance of a web page.*

**HTML Images Syntax**

- The HTML < img> tag is used to embed an image in a web page.

- Images are not technically inserted into a web page; images are linked to web pages. The < img> tag creates a holding space for the referenced image.

- The < img> tag is empty, it contains attributes only, and does not have a closing tag.

- The < img> tag has two required attributes:
>

   >`src` - Specifies the path to the image
   ---
 >`alt` - Specifies an alternate text for the image
**Syntax**

`<img src="src" alt="Smiley face">`


**Edit Images**

*The height, width, align and float  properties are used to set the image*

**Animated GIFs**

*Animated GIFs show several frames of animage in sequence*

**additional Info**

- You should save images at the size you will be using
them on the web page and in the appropriate format.
-  Photographs are best saved as JPEGs; illustrations or
logos that use flat colors are better saved as GIFs.

## Color


**CSS Color Values**

*With CSS, colors can be specified in different ways:*

- By color names
- As RGB values
- As hexadecimal values
- As HSL values (CSS3)
- As HWB values (CSS4)
- With the currentcolor keyword

Like this 

**RGB Colors**

*RGB color values are supported in all browsers.*

*An RGB color value is specified with: rgb( RED , GREEN , BLUE ).*

*Each parameter defines the intensity of the color as an integer between 0 and 255.*

**Example**






**CSS background-color Property**


`background-color: red;` OR 
`background-color:#fff025;`

**Definition and Usage**

*The background-color property sets the background color of an element.*

*The background of an element is the total size of the element, including padding and border (but not the margin).*


## Text

**Generic Font Families**

*In CSS there are five generic font families:*

1. Serif fonts have a small stroke at the edges of each letter. They create a sense of formality and elegance.
2. Sans-serif fonts have clean lines (no small strokes attached). They create a modern and minimalistic look.
3. Monospace fonts - here all the letters have the same fixed width. They create a mechanical look. 
4. Cursive fonts imitate human handwriting.
5. Fantasy fonts are decorative/playful fonts.



**example**

`.p1 {
  font-family: "Times New Roman", Times, serif;
}`

`.p2 {
  font-family: Arial, Helvetica, sans-serif;
}`

`.p3 {
  font-family: "Lucida Console", "Courier New", monospace;
}`



**Text-Decoration**



**Definition and Usage**

*The text-decoration property specifies the decoration added to text, and is a shorthand property for:*

- text-decoration-line (required)
- text-decoration-color
- text-decoration-style

**Example
Set different text decorations for `<h1>`, `<h2>`, and `<h3>` elements:**
--
`h1 {
  text-decoration: overline;
}`

`h2 {
  text-decoration: line-through;
}`

`h3 {
  text-decoration: underline;
}`

`h4 {
  text-decoration: underline overline;
}`

