sudo apt-get install ros-noetic-hector-mapping
sudo apt-get install ros-noetic-gmapping
sudo apt-get install ros-noetic-teb-local-planner
sudo apt-get install ros-noetic-hector-geotiff-launch
sudo apt-get install ros-noetic-move-base
sudo apt-get install ros-noetic-hector-mapping
sudo apt-get install ros-noetic-dwa-local-planner
sudo apt-get install ros-noetic-navigation

//close this repo in your catkin_ws
roslaunch hector_quadrotor_demo indoor_slam_gazebo.launch
//in other terminal
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
