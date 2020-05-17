# 2017BTECS00014_2017BTECS00045_2017BTECS00051
Pupil_Detection_using OpenCV and Python


Pupil detection from image of eye using OpenCV and Python

Steps to Detect the pupil -
 
1.Load the image

2.Make it invert

3.Convert to image to grayscale then convert to binary 

4.Apply Gaussian Blur

5.Define size of kernel and apply Erosion transform

6.Use binary filter by taking threshold value 210

7.Detect largest object by using circle method

8.Find centre point and height of the object

9.Highlight the area of concern
 
For the purpose of removing noise Gaussina Blur is used.Color Image Denoising technique is used for pre-processing on the image of eye before applying inversion filter.For the segmentation and contour detection we choose the nearest area of the centre of circle because eyeball will be near to center of the eye.

You can directly run it on google colab.



