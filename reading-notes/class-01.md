# Readings-Notes-Repository

## Class 01 notes for my Readings in Code Fellows 301 Course

[Back To Main](https://matthewadamstewart.github.io/readings-notes-repository/)


### Responsive Web Design

* This can all be found at: [Responsive Web Design](https://learn.shayhowe.com/advanced-html-css/responsive-web-design/)
* Responsive web design is the practice of building a website suitable for all devises regaurdless of platform or screen.
* term Coined by Ethan Marcotte who wrote a book


### Responsive versus Adaptive versus Mobile

*  > Responsive generally means to react quickly and positively to any change
* > Adaptive means to be easily modified for a new purpose or situation, such as change
* Very Similar in meaning and often used synonymously
* When both used together makes a great way to make functional websites
* > Mobile.. ...generally means to build a separate website commonly on a new domain solely for mobile users
* Occasionally appropriate but most often isn't (being exclusive in this sense reduces potential audience, not a common goal)

### Flexible Layouts
* Responsive web design has three main components
    * Flexible layouts
    * Media queries
    * Flexible media
* Flexible layouts
    * Is about using a grid which is flexible and able to change dynamically
    * These grids have squares which are changeable in relative size, using either percentages or em units
    * This is often done with declaring these properties: width, margin, padding
    * Does not recommend using a mixture of units due to complications and potential conflicts in measurment
    * Formula for calculating target width based on child/parant relationships: target ÷ context = result
* Relative Viewport Lengths
    * This is related to the viewport size and uses:
    * vw: Viewports width
    * vh: Viewports height
    * vmin: Minimum of the viewport’s height and width
    * vmax: Maximum of the viewport’s height and width
* Shows Example at [Scroll down to Flexible Grid from this Link](https://learn.shayhowe.com/advanced-html-css/responsive-web-design/#flexible-layouts) This was the closest ID which i could use as a link ;-)
* Media Queries
    * > Media queries provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example
    * Done via using separate CSS style sheets and using @media and @import rules
    * Examples
    * > ```<!-- Separate CSS File -->```
    > ```<link href="styles.css" rel="stylesheet" media="all and (max-width: 1024px)">```
    > ```/* @media Rule */```
    > ``` @media all and (max-width: 1024px) {...}```
    > ``` /* @import Rule */```
    > ``` @import url(styles.css) all and (max-width: 1024px) {...}```
    * Common Types of Media Queries: all, screen, print, tv, and braille
    * HTML5 has even more new types
        * Example: 3d-glasses
    * This is important enough to quote:
    * > The media query expression that follows the media type may include different media features and values, which then allocate to be true or false. When a media feature and value allocate to true, the styles are applied. If the media feature and value allocate to false the styles are ignored.
    * Logical Operators in Media Queries: ```and```, ```not```, and ```only```
    * ```and``` and ```not``` work as expected
    *  > The ```only``` logical operator is a new operator and is not recognized by user agents using the HTML4 algorithm, thus hiding the styles from devices or browsers that don’t support media queries.
    * Most commonly used to control height and width, often with min or max qualifiers
* Aspect Ratio Media Features
    * specifies the width/height pixel ratio of devise
    * uses two positive integers separated by a forward slash
    * Example: ```@media all and (min-device-aspect-ratio: 16/9) {...}```
* Pixel Ratio Media Features
    * pixel ratio feature is great for identifying high definition devices
* Resolution Media Feature
    * does accept the min and max prefixes. Additionally
    * will accept dots per pixel (1.3dppx), dots per centimeter (118dpcm), and other length based resolution values
* Other Media Features
    * color, color-index, and monochrome features, identifying bitmap devices with the grid feature, and identifying the scanning process of a television with the scan feature
    * not common but sometimes useful
* Media Query Browser Support
    * do not work within Internet Explorer 8 and below, as well as other legacy browsers
* Mobile First
    * Isn't mobile exclusive but is mobile focused
* Viewport
    * viewport meta tag was invented by Apple to help mobile devises display websites
    * when used with either the height or width values will define the height or width of the viewport 

* [1st book mark required](https://www.freecodecamp.org/news/css-floats-explained-by-riding-an-escalator-57fa55232333/)
* [2nd book mark required](https://css-tricks.com/dont-overthink-it-grids/)
* [3rd book mark required](http://smacss.com/)
