# Alertness_detection

    Motivation
    
In India, there are a lot of accidents taking place every day due to mishaps.As the no. of cars and accidents are increased as the population grows. This example program shows how to find frontal human faces in an image and estimate their pose. The pose takes the form of 68 landmarks. These are points on the face such as the corners of the mouth, along the eyebrows, on the eyes, and so forth.

    Idea

We are going to implement a special method and use it to determine how long a given person’s eyes have been closed. If their eyes have been closed for a certain amount of time, we’ll assume that they are starting to doze off and play an alarm to wake them up and grab their attention.

Apart from this, this will also test for the same condition of yawning. In this, if the person yawns it would prompt another alert alarm for this to make him/her caution. We will also execute another extra feature by providing the driver’s parents or closed ones specifying the detailed accurate response and expressions of the driver. 

This is only provided to the closed ones so that they can easily track the facial emotions and expressions of the driver seating in the car and let’s suppose when the driver’s response is Yawning a continuous vibration notification will be sent to their closed ones cell phone stating a message “Yawning while driving” so that they can take the required measures like calling or texting him/her to prevent causing accidents.

    Working

We’ll set up a camera that monitors a stream for face in the vehicle in front of the driver’s seat so that we could detect and apply facial landmark localization to monitor the eyes. If a face is found, we apply facial landmark detection and extract the eye regions.

Now that we have the eye regions, we can compute the eye aspect ratio in which we create a function to compute the ratio of the distance between verticle eye landmarks and horizontal eye landmarks. If the eye aspect ratio indicates that the eyes have been closed for a sufficiently small amount of time, the driver will sound an alarm.

We are using the application of machine vision and Image processing for this purpose with the use of OpenCV, dlib, Python, and ML to implement and run our algorithm. We are using Scipy package also for the euclidean distance between facial landmark points in the eye aspect ratio calculation.

When a user needs information about the driver as the radius between eyelids comes closer and the driver is about to fall asleep, their closed ones will receive continous popped up notifications and tapping the secured QR code can easily be scanned through their smartphones. Through this facial emotions and expressions of the driver in the vehicle can be detected so that his/her closed ones can call him to make minute chances of causing accidents.

    Use Case of the project

When Either no face is detected or the calculated aspect ratio is less than or equal to the threshold value, Nothing would be displayed.
When Mouth Aspect Ratio is greater than Mouth Threshold Value, Notification for ‘Yawning’ would be displayed.
When Eyes Aspect Ratio is greater than Eyes Threshold Value, Notification for ‘Sleeping’ would be displayed.
When Eyes Aspect Ratio and Mouth Aspect Ratio are greater than Eyes Threshold Value and Mouth Threshold Value respectively, Notifications for ‘Sleeping and Yawning’ would be displayed.

    Data Source
    
Shape Predictor 68 Face Landmarks
