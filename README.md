# Alertness_detection

   ## **PROBLEM STATEMENT**
   In India, there are a lot of accidents taking place every day due to mishaps. The no. of cars and accidents are increased as    the population grows. Most of the accidents take place due to people  feeling sleepy,high speed,drunk and drive.
   So,we are going to implement an accident prevention system which deals with the problem of accidents happening due to people    getting dozed off or feeling sleepy. 
   
   ## **APPLICATIONS**
This can be used by riders who tend to drive for a longer period of time that may lead to accidents

   
   ## **IDEA**
   A system that can automatically detect driver drowsiness in a real time video stream and then play an alarm if the driver      appears to be drowsy.
  
   
   ## **WORKING**
   Program shows how to find frontal human faces in an image and estimate their pose. 
   The pose takes the form of 68 landmarks.These are points on the face such as the corners of the mouth, on the eyes, and so forth.
   
   
   <img src="https://github.com/srss-BIProject/Alertness_detection/blob/master/images/shape.PNG">
   
   When Either no face is detected or the calculated aspect ratio is less than or equal to the threshold value, Nothing would be       displayed.
   When Mouth Aspect Ratio is greater than Mouth Threshold Value, Notification for ‘Yawning’ would be displayed.
   When Eyes Aspect Ratio is greater than Eyes Threshold Value, Notification for ‘Sleeping’ would be displayed. 
   When Eyes Aspect Ratio and Mouth Aspect Ratio are greater than Eyes Threshold Value and Mouth Threshold Value respectively,    Notifications for ‘Sleeping and Yawning’ would be displayed.
   
   ## **RELATIONSHIP**
   You can compute "Eye Aspect Ratio"(EAR) using the formula-
   
   
  <img src="https://github.com/srss-BIProject/Alertness_detection/blob/master/images/Ear.png">
  
  <img src="https://github.com/srss-BIProject/Alertness_detection/blob/master/images/Eye.jpg">
  
   
   ## **DATASET**
   
   -[Facial Landmarks](https://github.com/srss-BIProject/Alertness_detection/blob/master/facial_image_ar.csv)
  
 
  
  ##  **REFERENCES**
  - [Shape Predictor 68 Face Landmarks](http://dlib.net/face_landmark_detection.py.html)
  
  
  - [Real-Time Eye Blink Detection using Facial Landmarks](https://vision.fe.uni-lj.si/cvww2016/proceedings/papers/05.pdf)
  
   - [Drowsiness-detection](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)
   
 
   


----------------------------------------------
   
