The purpose of the project is to develop a software pipeline to estimate the lane linees on the road video and image.

The software uses advanced cimputer vision algorithms and estimates the lane line, with curvature and car offset

The software pipeline uses the following steps - 



Import and initialize the packages needed in the project
Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
Apply a distortion correction to raw images.
Use color transforms, gradients, etc., to create a thresholded binary image.
Apply a perspective transform to rectify binary image ("birds-eye view").
Detect lane pixels and fit to find the lane boundary.
Determine the curvature of the lane and vehicle position with respect to center.
Warp the detected lane boundaries back onto the original image.
Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.
Run pipeline in a video.

The algorithm can be further improved using advanced deep learning methods like convolutional neural nets and semantic segmentation.