# License-Plate-Recognition-System
This is an image processing project to detect the license plate.

+ I used bilateralFilter() to reduce distortion.
+ Then, I applied otsu to get thresholded image.
+ Then, I used opening operation to focus license plate more.
+ Then, I used Canny to get a clear view for license plate.
+ Then, I used findCountours() to detect the 4-pointed object.

This algorithm worked very well in most of the images. In a few images, algorithm chose some random 4-pointed object as license plate. 

![flowchart](https://user-images.githubusercontent.com/73538696/151668098-6af45007-c4a4-4851-9243-e4a45cba84b1.PNG)
