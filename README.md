# Hand_gesture_Recognition
Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognize five different gestures performed by the user which will help users control the TV without using a remote. The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

Thumbs up: Increase the volume
Thumbs down: Decrease the volume
Left swipe: 'Jump' backwards 10 seconds
Right swipe: 'Jump' forward 10 seconds
Stop: Pause the movie
Understanding the dataset
Each video is a sequence of 30 frames (or images). There are 663 videos provided as training data and 100 videos provided as validation data all images in a video subfolder have the same dimensions different videos may have different dimensions. Specifically, videos have two types of dimensions - either 360x360 or 120x160 There are two csv (one for train, one for validation) files having path of videos.

Approach
Our task is to train a model on the 'train' folder which performs well on the 'val' folder as well. Basically, there are two types of architecture commonly used for analyzing videos which we have used here in this case study: - Convolutions + RNN and 3D Convolutional Network, or Conv3D.
