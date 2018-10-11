# Vehicle_Number_Plate_Detection_Using_ImageProcessing
The project is an efficient algorithm  developed to detect a license plate in various luminance conditions. This algorithm extracts the license plate data from an image and provides it as an input to the stage of Car License Plate Recognition. This algorithm can be downloaded onto Texas Instrument’s TMS320DM6437 digital video development platform/RaspberryPie. The image of a vehicle is given as an input from the camera. Extracted image of the number plate can be seen on television for verification purpose.

Tools used

>  Windows 8.1 (operating system)  
>  MATLAB R2014a

Steps to be followed:
1. Run Matalb and set directory to folder which contains all of the files.
2. Get data set of img and char from https://drive.google.com/drive/folders/1uhNIXOsFpn0a3nu9FuicW6UUo3SaKSVk?usp=sharing
3. Run the main_code.m file in Matlab.
4. Change the image by editing the following lines of code in the main_code file

im = imread('img/car8.jpg')

Change to 

im = imread('img/car1.jpg')
im = imread('img/car2.jpg')
And so on

