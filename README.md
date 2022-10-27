# random-RGB-Hex-Generator
Click the button to generate a random RGB/hex code from a list of over 500 hex colors.
The button will display the RGB and the text below will display the RGB in hex.

The array colorList has over 500 hex color combinations inside of it. minimize the array to save scrolling.

With each click on the button, the function randomColor is called.
randomColor uses the length of the array to get a random element (hex code) and then assigns the value of the random element to the variable color.
color is then used to set the backgroundColor of the button and the innerText.

Instead of creating an array with multiple hex color combinations, you can just copy and paste the colorList array.
The logic behind the RNG and setting the button backgroundColor/innerText --> use lines 559-570.
