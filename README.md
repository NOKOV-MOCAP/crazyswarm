# Crazyswarm

A Large Nano-Quadcopter Swarm with nokov motion capture system native support, and vrpn is alternative.

![crazyswarm_deom](https://github.com/user-attachments/assets/ed2d763c-4dc3-406d-9e37-a9939d932ef2)

> **Warning**
> This repository is not actively maintained anymore. For new projects, please consider [Crazyswarm2](https://imrclab.github.io/crazyswarm2/).

The documentation is available here: http://crazyswarm.readthedocs.io/en/latest/.

## Quick start with motioncapture system

[Crazyswarm with nokov tutorial](https://robot-comm-cn-docs.nokov.com/qi-crazyflie-xiang-guan/er-nokovflie-shi-yong-shuo-ming)

```
git clone https://github.com/NOKOV-MOCAP/crazyswarm.git --recursive
cd ros_ws
catkin_make
source devel setup.bash
roslaunch crazyswarm hover_swarm.launch 
```
