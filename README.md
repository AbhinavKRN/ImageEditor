# ImageEditor
ImageEditor is a program to make creative changes on a particular image. It is written in Java Language.
This Java program is an image processing application that allows users to perform various image manipulation tasks on an input image. The program provides options to increase brightness, decrease brightness, convert to grayscale, rotate, and apply a blur effect to the input image. Users can specify the input and output file paths and choose the desired image processing operation.
 1. Introduction: 
This image processing application is implemented in Java and uses the Java AWT and ImageIO libraries for image manipulation. It provides a command-line interface for users to apply various image processing operations to an input image and save the processed image as an output.
	
 2. Installation 
There is no specific installation process required for this application. You need to have Java installed on your system to run the program. You can compile and run the Java source code using any Java development environment or the command line.

3. Use

To use this image processing application, follow these steps:

1. Compile the Java source code: `javac Image.java`
2. Run the program: `java Image`
3. Follow the on-screen instructions:
   - Enter the path to the input image file.
   - Enter the path for the output image file.
   - Choose one of the image processing operations (1-6) or exit (7).

 4. Functions:

-	convertToGrey

Converts the input image to grayscale.

-	increaseBrightness
Increases the brightness of the input image by a specified percentage.
-	decreaseBrightness
Decreases the brightness of the input image by a specified percentage.
-	rotate
Rotates the input image by a specified angle in degrees.
-	blur
Applies a blur effect to the input image with a specified radius.
-	Invert Image
Invert  the input image and give the output image.
-	saveImage
Saves the processed image to the specified output file path.
5. Main Method
The ‘main’ method of the program serves as the entry point. It handles user input, loads the input image, performs the selected image processing operation, and saves the resulting image to the output file.
6. Example Usage 
Here's an example of how to use the program:
1. Enter the path of the input image: `input.jpg`
2. Enter the path for the output image: `output.jpg`
3. Choose one of the following options:
   1: Increase Brightness
   2: Decrease Brightness
   3: Grayscale
   4: Rotate
   5`: Blur
   6. Invert
   7. exit
For example, if you choose option 1.Increase Brightness, the program will increase the brightness of `input.jpg` by 20% and save the result as `output.jpg`.
7. Conclusion
This Java image processing application provides a simple command-line interface for performing common image manipulation tasks on input images. Users can choose from various operations to modify images according to their requirements. It can be extended and customized to include additional image processing features or integrated into other applications as needed.


