1.Test Lidar YDX3
 roslaunch ydlidar_ros_driver X3.launch
 topic:
 rostopic echo /scan
2.Test map
roslaunch ydlidar_ros_driver lidar_view.launch
3.Hector slam
roslaunch ydlidar_ros_driver slam_mapping.launch
