# img.generator-blackmetal

hello! My name is J. Cadogan and this is a p5.js generative art sketch I wrote. I described it on twitter as a program that looks at your code and draws what it sees, but that isn't completely accurate (it was mostly for the bit). The code works by accessing the pixels of an img uploaded to an assets folder and generating curves correlated with the pixel position and color. I've included very basic notes in the actual code, here's a slightly more detailed step-by-step description of how to use this program.

CREATE A NEW SKETCH IN p5.js (I used the Web Editor)

After that, follow these steps:

1. Create "Assets" folder using the Sketch Files dropdown menu. 
2. Using the "Assets" folder dropdown menu, select "Upload file" and choose an image. If "Upload File" isn't an option, make sure you have an account and are logged in on the p5.js Web Editor. I recommend something fairly small, typically < 800 pixels in width or height, but any size should work. I've only used .jpg so far as well.
3. Copy and paste code into sketch.js work window.
4. Replace "IMG_NAME_HERE" with the name of your image file. 
5. Press the play button ("Run Sketch") to generate an image!

You can save a PNG of the generated image by right-clicking it in the preview window.

To change the quality of curves, try editing the values after "xPos, yPos," in the curve parameters. Adjust the noiseDetail or strokeWeight parameters to change the style of the piece overall.  

Enjoy!
