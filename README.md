## Google's Color Palette Sass Map & Function ##

Colors from **http://www.google.com/design/spec/style/color.html**

### Use case ###

Start the function `$google-color` then specify the color avalible from the map, then the variation. If no variation is entered then the standard `500` will be used.

`color: $google-color(red);` will produce `color: #F44336;`
`color: $google-color(green, 800);` will produce `color: #2E7D32;`

