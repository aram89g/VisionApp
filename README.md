# VisionApp
Autonomus Drone Control Using Grounded Stereo Cameras

This project designed to be part of the infrastructure for a more complex project' drone swarm.
In the project we used a grounded stereo system to aquire live images of a TELLO drone, from the images we calculated it's
3D coordinates by using stereo geometry. After that we used a PID controller in each of the drone axis (x,y,z) 
to send it a control command to fly to the designated target according to the flight plan file.
