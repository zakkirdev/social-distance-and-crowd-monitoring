# Social Distancing and Crowd Monitoring

## Description
The main goal of this application is to monitor social distancing and crowd by the method below:
1. Check distance between instances(people)
2. Display number of people entered the building and reduce it when people exited the building

The implementation of this application is by using computer vision and machine learning.
Pre-trained model is used to detect human and draw a centroid to represent one instance. The social distance is practised when people
have distance more than one meter and violating it if they less than one meter. The social distance is calculated pairwise of each 
instances detected in the video frame

## External Library

OpenCV, NumPy, TensorFlow
