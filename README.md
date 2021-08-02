# Number_Plate_Detection_System

This include code for number plate detection system.
We have used various techniques and libraries of Machine Learning to complete the task.

To achieve this , we have to do two major tasks:

(1)First is to detect a number plate from an image or video of a car. In this we have to isolate/crop the number plate from complete image which can then be used 
  to convert that image text.We are also storing the cropped image of the number plate for future use.
   We have used OpenCV to for number plate detection and cropping of the image. Image processing is done on the image to make it suitable for detection.
   Top 30 Contours(Outline bounding Shapes) are selected and as a number plate will always be a perfect 4 side contour so we select that and the cropped image is stored 
   for OCR
   
(2)Second task is to detect the number from cropped image and store it in a text form.This is done by doing OCR(Optical Character Recogniztion) with the help of Tessaract.
    This can also be done by using google API instead of Tessarct and it will give better results than that.
    
 
