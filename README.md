# loam_ws

1、启动hunter小车  
rosru hunter_bringup bringup_can2usb.bash
roslaunch hunter_bringup hunter_robot_base.launch

2、启动rslidar雷达
roslaunch rslidar_pointcloud rs_lidar_16.launch

3、启动loam
roslaunch lego_loam run.launch
