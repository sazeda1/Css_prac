# Css_prac
RGB Value
In CSS, a color can be specified as an RGB value, using this formula:

rgb(red, green, blue)

Each parameter (red, green, and blue) defines the intensity of the color between 0 and 255.

For example, rgb(255, 0, 0) is displayed as red, because red is set to its highest value (255) and the others are set to 0.

To display black, set all color parameters to 0, like this: rgb(0, 0, 0).

To display white, set all color parameters to 255, like this: rgb(255, 255, 255).

# RGBA Value
RGBA color values are an extension of RGB color values with an alpha channel - which specifies the opacity for a color.
An RGBA color value is specified with:
rgba(red, green, blue, alpha)

# HEX Value
In CSS, a color can be specified using a hexadecimal value in the form:

# rrggbb

Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).

For example, #ff0000 is displayed as red, because red is set to its highest value (ff) and the others are set to the lowest value (00).
To display black, set all values to 00, like this: #000000.
To display white, set all values to ff, like this: #ffffff.  

## HSL Value
In CSS, a color can be specified using hue, saturation, and lightness (HSL) in the form:
hsl(hue, saturation, lightness)

Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.

Saturation is a percentage value, 0% means a shade of gray, and 100% is the full color.

Lightness is also a percentage, 0% is black, 50% is neither light or dark, 100% is white

When using the shorthand property the order of the property values is:
background-color
background-image
background-repeat
background-attachment
background-position
It does not matter if one of the property values is missing, as long as the other ones are in this order. Note that we do not use the background-attachment property in the examples above, as it does not have a value.

## CSS Border Style
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

## CSS Border Width
The border-width property specifies the width of the four borders.
The width can be set as a specific size (in px, pt, cm, em, etc) or by using one of the three pre-defined values: thin, medium, or thick:
If the border-style property has four values:

## border-style: dotted solid double dashed;
top border is dotted
right border is solid
bottom border is double
left border is dashed
If the border-style property has three values:

## border-style: dotted solid double;
top border is dotted
right and left borders are solid
bottom border is double
If the border-style property has two values:

## border-style: dotted solid;
top and bottom borders are dotted
right and left borders are solid
If the border-style property has one value:

## border-style: dotted;
all four borders are dotted
## CSS Border - Shorthand Property
Like you saw in the previous page, there are many properties to consider when dealing with borders.
To shorten the code, it is also possible to specify all the individual border properties in one property.
The border property is a shorthand property for the following individual border properties:
border-width
border-style (required)
border-color

# CSS has properties for specifying the margin for each side of an element:

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

# Margin - Shorthand Property
To shorten the code, it is possible to specify all the margin properties in one property.
The margin property is a shorthand property for the following individual margin properties:
margin-top
margin-right
margin-bottom
margin-left
So, here is how it works:

If the margin property has four values:
margin: 25px 50px 75px 100px;
top margin is 25px
right margin is 50px
bottom margin is 75px
left margin is 100px

# Margin Collapse
Top and bottom margins of elements are sometimes collapsed into a single margin that is equal to the largest of the two margins.
This does not happen on left and right margins! Only top and bottom margins!

#CSS Padding
The CSS padding properties are used to generate space around an element's content, inside of any defined borders.
With CSS, you have full control over the padding. There are properties for setting the padding for each side of an element (top, right, bottom, and left).

# Padding - Individual Sides
CSS has properties for specifying the padding for each side of an element:
padding-top
padding-right
padding-bottom
padding-left

All the padding properties can have the following values:
length - specifies a padding in px, pt, cm, etc.
% - specifies a padding in % of the width of the containing element
inherit - specifies that the padding should be inherited from the parent element
Note: Negative values are not allowed.

# Padding - Shorthand Property
To shorten the code, it is possible to specify all the padding properties in one property.
The padding property is a shorthand property for the following individual padding properties:
padding-top
padding-right
padding-bottom
padding-left
So, here is how it works:
If the padding property has four values:
padding: 25px 50px 75px 100px;
top padding is 25px
right padding is 50px
bottom padding is 75px
left padding is 100px

# The CSS height and width properties are used to set the height and width of an element.
# The CSS max-width property is used to set the maximum width of an element.
# CSS Setting height and width
The height and width properties are used to set the height and width of an element.

The height and width properties do not include padding, borders, or margins. It sets the height/width of the area inside the padding, border, and margin of the element.

# CSS height and width Values
The height and width properties may have the following values:

auto - This is default. The browser calculates the height and width
length - Defines the height/width in px, cm etc.
% - Defines the height/width in percent of the containing block
initial - Sets the height/width to its default value
inherit - The height/width will be inherited from its parent value
# The CSS Box Model
In CSS, the term "box model" is used when talking about design and layout.

# The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. 
Explanation of the different parts:

Content - The content of the box, where text and images appear
Padding - Clears an area around the content. The padding is transparent
Border - A border that goes around the padding and content
Margin - Clears an area outside the border. The margin is transparent
The box model allows us to add a border around elements, and to define space between elements. 

# CSS Outline Style
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

# CSS Outline Width
The outline-width property specifies the width of the outline, and can have one of the following values:

thin (typically 1px)
medium (typically 3px)
thick (typically 5px)
A specific size (in px, pt, cm, em, etc)

# CSS Outline Color
The outline-color property is used to set the color of the outline.

The color can be set by:

name - specify a color name, like "red"
HEX - specify a hex value, like "#ff0000"
RGB - specify a RGB value, like "rgb(255,0,0)"
HSL - specify a HSL value, like "hsl(0, 100%, 50%)"
invert - performs a color inversion (which ensures that the outline is visible, regardless of color background)
