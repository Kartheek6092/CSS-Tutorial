# CSS-Tutorial
This is a finest repository of CSS programs from basic to a standard level.

CSS-SELECTORS
=============
We can divide CSS selectors into five categories:

*Simple selectors (select elements based on name, id, class)
*Combinator selectors (select elements based on a specific relationship between them)
*Pseudo-class selectors (select elements based on a certain state)
*Pseudo-elements selectors (select and style a part of an element)
*Attribute selectors (select elements based on an attribute or attribute value)
I have provided simple class selectors with practice code.

How to add CSS
==============
There are three ways of inserting a style sheet:

*External CSS
*Internal CSS
*Inline CSS
provided practice code for these three insertion types.

CSS Comments
============
Comments are used to explain the code, and may help when you edit the source code at a later date.
Comments are ignored by browsers.
A CSS comment is placed inside the <style> element, and starts with /* and ends with */:
 provided practice code for comments.
 
 CSS - colors
==============
Colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.
provided practice code for all types in colors.

CSS - Backgrounds
==================
The CSS background properties are used to add background effects for elements.

In these chapters, you will learn about the following CSS background properties:

*background-color
*background-image
*background-repeat
*background-attachment
*background-position
*background (shorthand property)
Practice code on these proerties are provided.

 CSS Borders
 ===========
 
 The CSS border properties allow you to specify the style, width, and color of an element's border.
 
 CSS Border Style
 -----------------
The border-style property specifies what kind of border to display.

The following values are allowed:

dotted - Defines a dotted border
dashed - Defines a dashed border
solid - Defines a solid border
double - Defines a double border
groove - Defines a 3D grooved border. The effect depends on the border-color value
ridge - Defines a 3D ridged border. The effect depends on the border-color value
inset - Defines a 3D inset border. The effect depends on the border-color value
outset - Defines a 3D outset border. The effect depends on the border-color value
none - Defines no border
hidden - Defines a hidden border
The border-style property can have from one to four values (for the top border, right border, bottom border, and the left border).
 The practice code is provided for al the border styles.


CSS Setting height and width
============================
The height and width properties are used to set the height and width of an element.

The height and width properties do not include padding, borders, or margins. It sets the height/width of the area inside the padding, border, and margin of the element.

CSS height and width Values
===========================
The height and width properties may have the following values:

auto - This is default. The browser calculates the height and width
length - Defines the height/width in px, cm etc.
% - Defines the height/width in percent of the containing block
initial - Sets the height/width to its default value
inherit - The height/width will be inherited from its parent value

CSS margins
===========
Margins are used to create space around elements, outside of any defined borders.

Margin - Individual Sides
--------------------------
CSS has properties for specifying the margin for each side of an element:

margin-top
margin-right
margin-bottom
margin-left
All the margin properties can have the following values:

auto - the browser calculates the margin
length - specifies a margin in px, pt, cm, etc.
% - specifies a margin in % of the width of the containing element
inherit - specifies that the margin should be inherited from the parent element
Tip: Negative values are allowed.
Practice code is provided.

Margin Collapse
===============
Top and bottom margins of elements are sometimes collapsed into a single margin that is equal to the largest of the two margins.

CSS padding
===========
Padding is used to create space around an element's content, inside of any defined borders.
Padding - Individual Sides
CSS has properties for specifying the padding for each side of an element:

padding-top
padding-right
padding-bottom
padding-left
This does not happen on left and right margins! Only top and bottom margins!
Practiec code is provided.

CSS Setting height and width
============================
The height and width properties are used to set the height and width of an element.

The height and width properties do not include padding, borders, or margins. It sets the height/width of the area inside the padding, border, and margin of the element.
CSS height and width Values
---------------------------
The height and width properties may have the following values:

auto - This is default. The browser calculates the height and width
length - Defines the height/width in px, cm etc.
% - Defines the height/width in percent of the containing block
initial - Sets the height/width to its default value
inherit - The height/width will be inherited from its parent value
Practice code is not provided.

CSS Outline Style
=================
The outline-style property specifies the style of the outline, and can have one of the following values:

dotted - Defines a dotted outline
dashed - Defines a dashed outline
solid - Defines a solid outline
double - Defines a double outline
groove - Defines a 3D grooved outline
ridge - Defines a 3D ridged outline
inset - Defines a 3D inset outline
outset - Defines a 3D outset outline
none - Defines no outline
hidden - Defines a hidden outline
Practice code is provided for all outline styles.

Text Color
===========
The color property is used to set the color of the text. The color is specified by:

a color name - like "red"
a HEX value - like "#ff0000"

CSS Text Alignment and Text Direction
=====================================
In this chapter you will learn about the following properties:

text-align
text-align-last
direction
unicode-bidi
vertical-align
an RGB value - like "rgb(255,0,0)"

All CSS text-decoration Properties
----------------------------------
Property	Description
text-decoration	Sets all the text-decoration properties in one declaration
text-decoration-color	Specifies the color of the text-decoration
text-decoration-line	Specifies the kind of text decoration to be used (underline, overline, etc.)
text-decoration-style	Specifies the style of the text decoration (solid, dotted, etc.)
text-decoration-thickness	Specifies the thickness of the text decoration line

Text Transformation
-------------------
The text-transform property is used to specify uppercase and lowercase letters in a text.
It can be used to turn everything into uppercase or lowercase letters, or capitalize the first letter of each word:

The CSS Text Spacing Properties
-------------------------------
Property	Description
letter-spacing	Specifies the space between characters in a text
line-height	Specifies the line height
text-indent	Specifies the indentation of the first line in a text-block
white-space	Specifies how to handle white-space inside an element
word-spacing	Specifies the space between words in a text
Practice code is not provided.

Font Selection is Important
===========================
Choosing the right font has a huge impact on how the readers experience a website.

The right font can create a strong identity for your brand.

Using a font that is easy to read is important. The font adds value to your text. It is also important to choose the correct color and text size for the font.

Generic Font Families
In CSS there are five generic font families:

Serif fonts have a small stroke at the edges of each letter. They create a sense of formality and elegance.
Sans-serif fonts have clean lines (no small strokes attached). They create a modern and minimalistic look.
Monospace fonts - here all the letters have the same fixed width. They create a mechanical look. 
Cursive fonts imitate human handwriting.
Fantasy fonts are decorative/playful fonts.
All the different font names belong to one of the generic font families.

Best Web Safe Fonts for HTML and CSS
-------------------------------------
The following list are the best web safe fonts for HTML and CSS:

Arial (sans-serif)
Verdana (sans-serif)
Helvetica (sans-serif)
Tahoma (sans-serif)
Trebuchet MS (sans-serif)
Times New Roman (serif)
Georgia (serif)
Garamond (serif)
Courier New (monospace)
Brush Script MT (cursive)

Commonly Used Font Fallbacks
----------------------------
Below are some commonly used font fallbacks, organized by the 5 generic font families:

Serif
Sans-serif
Monospace
Cursive
Fantasy

Font Style
----------
The font-style property is mostly used to specify italic text.

This property has three values:

normal - The text is shown normally
italic - The text is shown in italics

The CSS Font Property
---------------------
To shorten the code, it is also possible to specify all the individual font properties in one property.

The font property is a shorthand property for:

font-style
font-variant
font-weight
font-size/line-height
font-family
Note: The font-size and font-family values are required. If one of the other values is missing, their default value are used.
oblique - The text is "leaning" (oblique is very similar to italic, but less supported)

