# The Art of CSS 
 **imagine that there is an invisible box around every HTML element,how would you style it?,what colors and designes you want to import in order to bring life into your website bages?** **well the answer of these quistions would be symple by CSS**

## wha is CSS ?
 
CSS or cascadind style sheet is a languge works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration
**Selectors** indicate which element the rule applies to fr example p element. The same rule can apply to more than one element if you separate the element names with commas
**Declarations** indicate how the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value), and are separated by a colon {}

**Properties** indicate the aspects of the element you want to change. For example, color, font, width, height and border
**Values** specify the settings you want to use for the chosen properties. For example, if you want to specify a color property then the value is the color you want the text in these elements to be 

## Now! Let's tak more about specific properity which is th COLOR

The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways :
* RGB values;These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100, 100,90)
*  HEX codes; These are six-digit codes that represent the amount of red,green and blue in a color,preceded by a pound or hash # sign. For example: #ee3e80
* color names;There are 147 predefined color names that are recognized by browsers. For example: DarkCyan

and if you want to add a comment in your code only you can put it between /* value */ symbol in order to mention the color above the css code.
*remember that we mentiond that css treats each HTML element as it appears surrounded by a box* so here we use th **background-color** property,andIf you do not specify a background color, then the background is transparent.  

## Color picker
Computer monitors are made up of thousands of tiny squares pixels (if you look very  at your monitor you should be able to see them).The color of every pixel on the screen is expressed in terms of a mix of red, green, and blue — just like on a television screen.Color picking tools are available
in image editing programs like Photoshop and GIMP. You can see the RGB values specified next to the radio buttons that say R, G, B.The hex value is providednext to the pound or hash #symbol. There is also a good color picking tool at[colors](colorschemedesigner.com)

**REG VALUSE** | **HEX CODE** | **COLOR NAME**
--------------- | -------------- | --------------
Values for red, green, and blue are expressed as numbers between 0 and 255 | Hex values represent values for red, green, and blue in hexadecimal code. | Colors are represented by predefined names.they are very limited in number
rgb(102,205,170) | #66cdaa | MediumAquaMarine

## contrast 
Text is harder to read when there is low contrast between background and foreground colors.CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).
background-color: rgb(0,0,0)
                 opicity(0.02)
                   
CSS3 introduces an entirely new and intuitive
way to specify colors using hue, saturation,
and lightness values

**HAUE** | **SATURATION** | **LIGHTNESS**
Hue is the colloquial idea of color. In HSL colors, hue is often represented as a color circle where the angle represents the color, although it may also be shown as a slider with values from 0 to 360 | Saturation is the amount of gray in a color. Saturation is represented as a percentage. 100% is full saturation and 0% is a shade of gray | Lightness is the amount of white (lightness) or black (darkness) in a color. Lightness is represented as a percentage. 0% lightness is black, 100% lightness is white, and 50% lightness is normal. Lightness is sometimes referred to as luminosity
