# HVID Measurement

This is an effort to measure HVID *(Horizontal Visible Iris Diameter)* using **Python** and **Computer Vision** from images taken from a *smart phone*.

Due the ever increasing demand of AI solutions in medical field, new algorithms are developed every year. The Corneal Diameter or HVID *(Horizontal Visible Iris Diameter) is extremely crucial for designing nice fitting **contact lenses**. 

In this attempt, I used basic computer vision and image processing tools for processes like detection and segmentation

In this project, i used **One Plus 7T** smart phone to take the images. Images were taken at a fixed distance **(10cm)**. Data such as image sensor dimensions, focal length of the sensor lens and aspect ratio are some of the key factors which are required to calculate the real time radius of the image 

This algorithm goes over  4 major steps:
 - Image Preprocessing
 - Detection
 - Segmentation
 - Calculation(Mean Radius and HVID)

# Note:
The algorithm is still under development. This is the stable and simple version of my original algorithm which should work perfectly but you cannot input your own images unless if you use the same device of mine. You may have to change parameters according to your camera specifications.

**I will be adding the sample input,output images soon within proper folders. In the meantime, i welcome you to explore the code as you wish**
