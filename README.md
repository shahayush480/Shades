# Shade.scss

The name "Shade" can convey a sense of depth, dimension, and variation in color. It also aligns with the idea of using CSS to add visual shading and depth to web pages. 

## about this project 
 - Shade can refer to the degree of darkness or lightness in a color, which is a key aspect of CSS/SCSS and design.
 - Shade can also refer to a shelter or protection from light, which could be a nod to the idea of the framework providing structure and support for developers.
 - Additionally, "shade" has a cool and trendy vibe that could make it a memorable and catchy name for a framework.

## tables of content

- quick start
- documentation

## documentation

There are 2 ways to use this setup
### basic way for beginners
- just download css file and use in your project

### grid division... create your own grid columns
To use this grid system, you can simply add the appropriate class to the parent container of your HTML elements. For example, if you want to create a grid with 3 columns, you can add the class "grid-3" to the parent container. Then, any child elements of that container will be displayed as a grid with 3 columns.

Here is an example of how you can use this grid system in your HTML code:
```
<div class="grid-3">
  <div>Element 1</div>
  <div>Element 2</div>
  <div>Element 3</div>
  <div>Element 4</div>
  <div>Element 5</div>
  <div>Element 6</div>
</div>
```

### advanced way
- make sure that you have installed node and npm in your system 
- clone this repo ```https://github.com/shahayush480/default-setup.git``` 
- use ```npm install``` and then ```npm start``` to run this repo
- here you go with our project setup and now you can customisie most of things in this code and get the code you want in your project 



## ignore below this it is still in progress

This is a SASS code snippet that defines two maps, $colors and $breakpoints.

The $colors map contains various color values, grouped into two categories: theme colors and system colors. Theme colors are named according to their intended usage, such as 'primary', 'secondary', and 'accent', and have three variants each: light, regular, and dark. System colors, on the other hand, are named based on their actual color, such as 'pure-white', 'pure-black', and 'grey', and also include a few named colors for specific purposes, such as 'info', 'error', 'success', and 'warning'.

The $breakpoints map contains the breakpoints for the responsive design of the website, with each key being a name for the breakpoint, such as 'xs', 'sm', 'md', 'lg', 'xl', and 'xxl', and each value being the corresponding width in pixels. These breakpoints can be used in conjunction with SASS's built-in mixins, such as @media screen and (min-width: map-get($breakpoints, sm)) to apply styles only to screens with a width greater than the value defined for the 'sm' breakpoint.


Documentation for the CSS Code
This is a set of CSS styles that defines a color palette and some default styles for HTML elements.

Color Palette
The color palette is defined using custom properties. Each color has a light, regular, and dark shade, plus some other colors used for backgrounds or text.

Primary Colors
--primary-light: #9ce5e9
--primary: #2ec9d1
--primary-dark: #1d7d82
Secondary Colors
--secondary-light: #7e1c79
--secondary: #d12ec9
--secondary-dark: #e898e4
Accent Colors
--accent-light: #84891e
--accent: #c9d12e
--accent-dark: #e3e794
Other Colors
--pure-white: #fff
--pure-black: #000
--white: #f7f7fa
--black: #212529
--grey: #ccc
--grey-light: #efefef
--grey-dark: #6c757d
--neutral: #28293d
--info: #0163f7
--error: #ff3c3a
--success: #09c270
--warning: #fe8800
To use one of these colors, you can reference it using the custom property. For example, to set the text color to the primary light color, you would use color: var(--primary-light);.

Default Styles
The CSS also includes some default styles for HTML elements, which you can use as a starting point for your own styles.

Reset Styles
The first part of the CSS applies a set of reset styles to all elements, removing margins, padding, and setting the box-sizing property to border-box.

Font Styles
The font-family property is set to a fallback list of system fonts, with the primary font being Arial. The font-size is set to 1.4rem for most elements, with some exceptions for headings and other elements.

Heading Styles
The headings (h1 to h6) have font-sizes ranging from 1.4rem to 2.8rem, with larger sizes on larger screens. They also have a margin of half the default spacing above and below.

Body Styles
The body element has a background-color of the --grey-color custom property (not defined in the code shared) and all links have no underline by default.

Color Styles
Finally, the CSS defines a set of text and background color classes for each color in the palette. These can be used to set the color of text or background by applying the relevant class to the element.