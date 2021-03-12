# number-plate-recognition-code
Here it will display the vehicle number plate after doing image detection using  OpenCV and Pytesseract packages 
We will implement Automatic License Number Plate Recognition using Gaussian Blur and Sobel.
Gaussian Blur:
Here we use a Gaussian kernel to smoothen the image. 
This technique is highly effective to remove Gaussian noise. 
OpenCV provides a cv2.GaussianBlur() function for this task.
Sobel :
Here we calculate the derivatives from the image. 
This feature is important for many computer vision tasks. 
Using derivatives we calculate the gradients, and a high change in gradient indicates a major change in the image. 
OpenCV provides a cv2.Sobel() function to calculate Sobel operators.
Morphological Transformation :
These are the operations based on image shapes and are performed on binary images. 
The basic morphological operations are Erosion, Dilation, Opening, Closing.
The different functions provided in OpenCV are:
cv2.erode()
cv2.dilate()
cv2.morphologyEx()
Contours: 
Contours are the curves containing all the continuous points of same intensity. These are very useful tools for object recognition. OpenCV provides cv2.findContours() functions for this feature.
