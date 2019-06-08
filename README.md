# Map My World

Project "Map My World" for Udacity Robotics Software Engineer course.

To launch:

 1. Clone this repo inside your catkin workspace (below /src)
 2. Run `catkin_make`
 3. Install required dependencies (see below)
 4. Run `roslaunch my_robot world.launch` to launch gazebo with the world & the robot
 5. In a separate terminal, run `roslaunch my_robot teleop.launch` to be able to control the robot via keyboard
 6. In a separate terminal, run `roslaunch my_robot mapping.launch` to launch the RTAB-Mapping
 
## Dependencies

* rtabmap_ros: `sudo apt-get install ros-kinetic-rtabmap-ros`
* `rosdep -i my_robot`
