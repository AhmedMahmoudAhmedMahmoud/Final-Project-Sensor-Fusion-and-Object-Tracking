# Writeup: Track 3D-Objects Over Time

Please use this starter template to answer the following questions:

### 1. Write a short recap of the four tracking steps and what you implemented there (filter, track management, association, camera fusion). Which results did you achieve? Which part of the project was most difficult for you to complete, and why?

In General, 
1- For filtering, We used kalman filter to predict the location of the object in the next frame 
2- For tracking management, Each track contains information such as the object's current position, its trajectory, and its unique identifier
3- For associating, It predicts location of the object in the current frame with its actual location
4- For camera fusion, It tracks from multiple camera views to get a complete picture of the object's movement in the environment

And in my opinion the most difficult part it was association, Because step since we had to deal with multiple objects appearing and disappearing in different frames 

### 2. Do you see any benefits in camera-lidar fusion compared to lidar-only tracking (in theory and in your concrete results)? 

Yes sure, It improved object detection, improved accuracy and robustness, Reduced false postives and false negatives

### 3. Which challenges will a sensor fusion system face in real-life scenarios? Did you see any of these challenges in the project?

It faces Calibration, Quality (because we use the sensor in a diffrent enviroment), Sensor synchronization, Computational complexity.
No, I didn't because I worked in a pre-recorded data and it was already synchronized and calibrated
 

### 4. Can you think of ways to improve your tracking results in the future?

Yes, we can improve object detection accuracy, Use more sensors, Improve association algrithms, Improve camera and lidar calibration and use more advanced camera and lidar fusion teqniques.
