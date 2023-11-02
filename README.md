# card-recognition
I started off importing libraries.
A list of images of UNO cards were created 
Manually created a labels list reperesenting the list of images 
The images are then read by opencv and threshold values were tuned to be readable to contour out the biggest contour
the biggest contour is the size of the whole card and this is cropped out.
Each of these cards go through colour thresholding and manually crop from the centre
the contour round the number is the second largest contour 
The features of the contours are then appended to the data index
the labels and feature data are then fed into the classifier to check the accuracy level of recognition
