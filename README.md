# Exercise-tracker-using-Mediapipe
The model is used to count the reps of knee bending exercise performed by the user. It also includes a timer of 8 seconds to ensure proper execution of the exercise. For this, it captures a video, applies a Kalman filter to reduce the fluctuation of keypoints, calculates the angle between hip, knee and ankle, implements rep counter and a timer, and writes the output to a file "output.mp4". It uses MediaPipe library to extract the landmarks and OpenCV library for the implementation of Kalman filter. The Kalman filter is initialized with the initial position of the knee, and then it is used to predict the next position of the knee based on its past positions and measurements. It also includes a try-except block to handle cases when the landmarks are not detected in a frame due to low lighting or occlusion.

## Video Demonstration

https://github.com/system-reboot/Exercise-tracker-using-Mediapipe/assets/98401163/0799c8b1-51ab-470d-962c-9be593a4a25f

