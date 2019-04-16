README
==============================

****
|Author|ZhangHongda|
|------|-----------------|
|E-mail|2210010444@qq.com|
|Institute|Harbin Institute of Technology|
****
# move_ur5_qt
A graphical user interface designed for trajectory programming by demonstration for UR5 robot.
### Installation
Step 1: clone the repository into your own workspace
```
cd ${PATH_TO YOUR_WORKSPACE_FOLDER}/src
git clone https://github.com/Zhang-Hongda/move_ur5_qt
```
Step 2: building
```
catkin_make
```
Step 3: activate the workspace
```
source ${PATH_TO YOUR_WORKSPACE_FOLDER}/devel/setup.bash
```
### Preparations
* Install the [pcl_tracker](https://github.com/Zhang-Hongda/pcl_tracker) package and finish the preparation steps.
* Follow the installation guidance in [universal_robot](https://github.com/ros-industrial/universal_robot) package. 
* Install the [ur_modern_driver](https://github.com/Zhang-Hongda/ur_modern_driver) package if you are using a UR version 3.0 and above, and make sure the robot is well connected.
