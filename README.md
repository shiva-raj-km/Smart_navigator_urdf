# Smart_navigator_urdf
SolidWorks model extraction into URDF
The Smart Navigator 3D model was constructed using SolidWorks design software. The model is analyzed for stress and strain of payload 100Kg. Using SW2URDF plugin the URDF file is extracted.

## Prerequisites
ROS framework should be installed.
## Setup
```bash
git clone https://github.com/shiva-raj-km/Smart_navigator_urdf.git
# cut & copy the urdf_4 folder into src folder of workspace
```

## Usage
``` bash
# Terminal -1
roscore # Run the ROS master
# Terminal -2
# source the workspace
roslaunch urdf_4 display.launch # to view in rviz

# To view the simulation in gazebo
roslaunch urdf_4 gazebo.launch
```
## Results
* Rviz
![navigator in Rviz](https://github.com/shiva-raj-km/Smart_navigator_urdf/blob/master/rviz.png)

* Gazebo
![navigator in Gazebo simulator](https://github.com/shiva-raj-km/Smart_navigator_urdf/blob/master/gazebo.png)
