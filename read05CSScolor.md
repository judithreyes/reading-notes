# CSS Chapter 10 Notes: Introducing CSS

## How CSS associates with HTML

The rules of CSS are made to work hand in hand with HTML. HTML is the structure and content of a web page, while CSS is how you will design the web page and change the way it looks, while keeping the HTML content. 

A CSS rule contains two parts:

1. Selector-this indicates which element the rule will apply to. The same rule can apply to more than one element if each element is separated by a comma. 

2. Declaration-this tells you how the element should be styled. Declarations are split intwo two parts, a property and a value. 

### Properties and Values

Properties indicate the aspects of the element you want to change, such as color, font, width, height, and border. Values indicate the settings that you want to use for a property. A property and value are separated by a semi-colon. 

Your CSS code should be in a separate page from your HTML code, although it is possible for your CSS to be on the same HTML page. It is just easier to understand if it's separate. 

# CSS Chapter 11 Notes: Color

## Foreground Color

This is a color property that lets you specify the color of text that is inside an element. You can choose or specify color in CSS using three different ways:

1. RBG values: you can change your color number value through red, green and blue tones. Numbers are between 0 and 255. An example would look like: rbg(100, 100, 90).

2. Hex codes: comprised of 6 digit codes that represent the amount of red, blue, and green in a color. Hex codes contain a # before. An example: #ee3e80.

3. Color names: there are 147 predefined color names that you can choose from. You can simply type out a color you would like, such as red or pink.

### Background Color

A background color is typically chosen for your text box. You can choose a background color the way foreground colors are chosen, through RBG values, hex codes, and color names. 

### CSS3 RGBA

This allows you to change the opacity in an element. The value is between 0.0 and 1.0. 

### CSS3 HSL & HSLA

This is an alternative way to specify colors. It uses hue, saturation, lightness, and alpha. 
