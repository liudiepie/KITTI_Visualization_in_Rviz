# KITTI Visualization in Rviz (unofficial)
This visualization is a re-implementation of The KITTI Vision Benchmark Suite based on the [website](http://www.cvlibs.net/datasets/kitti/index.php)
##### Including carema, point cloud, 3d boxes, imu data, gps data, tracking location and min distance between other objects
![image](https://github.com/liudiepie/ROS_practice/blob/master/view.gif)

# Installation
* ## Environment
   ### Ubuntu 20.04
   [Ubuntu 20.04](https://ubuntu.com/download/desktop)
   ### Python 3.8
   > os, numpy, cv2, rospy, pandas,
* ## Data
   ### Raw Data
   Download 2011_09-26_drive_0005 from website above
   Convert KITTI dataset into ROS bag files
   ```bash
   sudo pip install kitti2bag
   kitti2bag -t 2011_09_26 -r 0005 rawsynced
   ```
