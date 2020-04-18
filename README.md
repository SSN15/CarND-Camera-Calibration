## Camera Calibration with OpenCV

The IPython notebook in this repository contains code to calculate the camera matrix and distortion coefficients using the images in the "calibration_wide" folder.

Steps:
Extract Object points and Image points using OpenCV functions
Then iterate over the list of images to calibrate camera aand undistort images using OpenCV functions

OpenCV functions used:
1. cv2.findChessboardCorners
2. cv2.drawChessboardCorners
3. cv2.calibrateCamera
4. cv2.undistort

Note: For Gray image conversion BGR2Gray is used because we are using glob API to read images
