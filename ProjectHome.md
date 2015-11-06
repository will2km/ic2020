# iC2020 #
### A Fourth Year University of Waterloo Design Project ###
Code written by Sean Anderson and Kirk MacTavish

Our goal is to use PrimeSense technology in order to create a globally consistent dense 3D colour map.

## Current accomplishments ##

  * Optical Flow using Shi Tomasi Corners
  * Visual Odometry using Shi Tomasi and GPU SURF
    * Features undergo RANSAC to find inliers (in green)
    * Least Squares is used across all inliers to solve for rotation and translation
  * Loop closure detection using a dynamic feature library
  * Global Network Optimization for loop closure

## Underlying Technology ##

  * Basic ROS Utilities
  * OpenCV
  * GPUSURF
  * TORO (openslam.org)

## Download and Installation ##
See source tab above and [Installation](Installation.md).