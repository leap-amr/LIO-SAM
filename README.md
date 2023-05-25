# Overview
LIO-SAM package for ROS Noetic

# Clone this package
``` cmd
cd ~/catkin_ws/src
git clone https://github.com/leap-amr/LIO-SAM
```

# Run this package
``` cmd
roscore &
roslaunch lio_sam run.launch
```

# rqt_graph
![lio-sam-glaph](https://user-images.githubusercontent.com/37500115/235294461-ceee0398-caa2-4892-8a2d-e92d26930df7.png)


# rosnode
launch : `lio_sam/run.launch`
node list:
``` cmd
```

# rostopic
launch : `lio_sam/run.launch`
topic list :
``` cmd
xavier@ubuntu:~$ rostopic list
/diagnostics
/gps/fix
/imu_correct
/imu_raw
/joint_states
/lio_loop/loop_closure_detection
/lio_sam/deskew/cloud_deskewed
/lio_sam/deskew/cloud_info
/lio_sam/feature/cloud_corner
/lio_sam/feature/cloud_info
/lio_sam/feature/cloud_surface
/lio_sam/imu/path
/lio_sam/mapping/cloud_registered
/lio_sam/mapping/cloud_registered_raw
/lio_sam/mapping/icp_loop_closure_corrected_cloud
/lio_sam/mapping/icp_loop_closure_history_cloud
/lio_sam/mapping/loop_closure_constraints
/lio_sam/mapping/map_global
/lio_sam/mapping/map_local
/lio_sam/mapping/odometry
/lio_sam/mapping/odometry_incremental
/lio_sam/mapping/path
/lio_sam/mapping/slam_info
/lio_sam/mapping/trajectory
/odometry/gps
/odometry/gpsz
/odometry/imu
/odometry/imu_incremental
/odometry/navsat
/points_raw
/rosout
/rosout_agg
/set_pose
/tf
/tf_static
```



