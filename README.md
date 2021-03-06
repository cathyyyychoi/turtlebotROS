# Capstone Design
## Implement of Indoor Object Seeking Robot
* Robot os: ROS kinetic
* Remote PC os: Ubuntu 16.04
* Hardware: turtlebot3 Waffle Pi 
* Algorithm: Active Neural Slam Algorithm
* Semantic Curiosity for Active Visual Learning
### Project Goal
* Understanding and Using SLAM
* Mapping and Localization by using Active Neural Slam [here](https://github.com/devendrachaplot/Neural-SLAM)
* Object Detection by using YOLO [here](https://pjreddie.com/darknet/yolo/)
* Semantic Curiosity Active Visual Learning [here](https://www.cs.cmu.edu/~dchaplot/projects/SemanticCuriosity.html)
### Method
* PC: Ubuntu 18.04 (4-core GPU, docker)
* Environment: habitat-sim, Python3.7
* Exchange data with Turtlebot (ex. sensor data)
  * Pi camera, RGB-D senser
* How to get sensor data from robot to simulation environment?
* Pre-task: Passive SLAM exploration
* Add Object Detection module
### Related Challenge
* Habitat Challenge 2020 | AI Habitat
#### Difficulties
* How to handle RGB-D data from Pi-camera?
* Resolution of Pi-camera
* How to put data in Neural SLAM?
