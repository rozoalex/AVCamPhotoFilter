# Intro
This project is for providing depth vision for ROS robots by using the dual lense system on iPhones.

## Main component:
1. Capuring depth
        This part takes advantages of the project AVCamPhotoFilter by dparksports: https://github.com/dparksports/AVCamPhotoFilter
2. Sending data to Linux system running ROS. (A node on that system will convert the data to ROS messeges and publish it)
        This part utilizeds API developed by Jonas Tjahjadi and Ben Winschel: https://github.com/campusrover/ros_hum_interaction
        

