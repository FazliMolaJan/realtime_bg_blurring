# Real Time Background Blurring using DeeplabV3

## Quick summary
This is the code to detect the parking space for the car given 2D image from the google maps and 3D point Cloud data of the current enivornment.

## Purpose
This project was made for the purpose of the AIS LAB.

This repository contains:

- 2D Lane Detection
- 3D parking detection

## Results
* Initial data 2D image taking from the google image and plotting the lines using OpenCV

![InitialData](images/initialdata.png)

* Applying filters to enhance the lines of the parking spots
![LaneDetection2D](images/2d.png)

* 3D data of the parking area collected by laser sensors and then used using Point Cloud Library
![3D-Data](images/3D_Data.png)

* Converting 2D image to 3D space so later it can be combine with 3D data 
![2Dto3D](images/2dto3d.png)

* Applying machine learning algorithm, linear regression to detect parking spots in 3D space and combining it with the 2D image data
![FinalResult](images/Final.png)

* Enchancing result by Applying logistic regression
![Result](images/Final2.png)

## Requiremnts
For this project to run you need:
* Visual Studio 2012
* OpenCV 3.0
* Point Cloud Library

### Who do I talk to? ###
I would be happy to talk to you about this project and if you are interested then we can further enhance this project to.

### Contact
* Amanullah Tariq 
* Email: amanullah.tariq@gmail.com
