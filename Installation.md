# Introduction #

Welcome to our code repository. We've posted the source code that we've been working on for the last few months. We hope someone will find it useful!

Just a warning, but this code was thrown together fairly quickly, it will probably not be easy to understand, commenting is fairly minimal, etc.


# Details #

Additional things you will need:
  * ROS (we used cturtle)
  * ROS's kinect package (the deprecated one)
  * GPU SURF ( http://homes.esat.kuleuven.be/~ncorneli/gpusurf/ )

Just to give a quick overview of the system flow:
  1. kinect\_camera
  1. ic2020\_optflow
  1. ic2020\_surf
  1. ic2020\_vodom
  1. ic2020\_loop
  1. ic2020\_toro
  1. ic2020\_render

For those of you familiar with our video:
http://www.youtube.com/watch?v=MafVZQDgmsk

We developed a modified version of kinect\_camera that streams the colour and disparity image over a wireless-N network. That code has not been cleaned at all, so we will not be releasing it as of now.