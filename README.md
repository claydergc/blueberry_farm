# simulated_blueberry_farm_environment
A simulated blueberry farm environment that runs in Gazebo. This farm environment is a modified version of the [outdoor agricultural world](https://clearpathrobotics.com/blog/2020/07/clearpath-robots-get-new-gazebo-simulation-environments/) by Clearpath Robotics.

If you use this code in an academic context, please cite the following paper:

Ricardo Jesus Huaman Kemper, Clayder Gonzalez, Sixto Ricardo Prado Gardini: Autonomous Navigation of a Four-Wheeled Robot in a Simulated Blueberry Farm Environment, IEEE Andean Conference (ANDESCON), 2022.

```
@INPROCEEDINGS{9989865,  
author={Kemper, Ricardo Jesus Huaman and Gonzalez, Clayder and Gardini, Sixto Ricardo Prado},  
booktitle={2022 IEEE ANDESCON},   
title={Autonomous Navigation of a Four-Wheeled Robot in a Simulated Blueberry Farm Environment},   
year={2022},  
volume={},  
number={},  
pages={1-6},  
doi={10.1109/ANDESCON56260.2022.9989865}}
```

## Installation and Use

This world has been tested in Ubuntu 18.04 and 20.04. 

```
cd ~/catkin_ws/src
git clone https://github.com/claydergc/blueberry_farm.git
roslaunch blueberry_farm blueberry_farm.launch 
```

## Environment details
### Environment dimensions
The area where the blueberry bushes are located is 9.98 m in the x-axis and 8.60 m in the y-axis. Additionally, the distance between crop rows is 1.40 m width. 
### Blueberry bush
The blueberry bush 3D model’s dimensions are 0.65 m × 0.60 m × 0.55 m. 
### Shack
The shack 3D model’s dimensions are 2.44 m × 2.40 m × 3.75 m.
