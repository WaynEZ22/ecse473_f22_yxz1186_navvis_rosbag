# ecse473_f22_yxz1186_navvis_rosbag
## Introduction
This package is built for lab3 in ECSE 473 at Case Western Reserve Univeristy. The purpose is to combine maps and sensor datas with a built robot model with laser scanners.
## Instructions
One Launch file is included within the lackage. The file has two different arguments:
- use_xacro_new: when true, it gives the robot new links and joints, including base_link and imu, and also enable user to see maps and sensor datas.
- use_xacro: this determines whether to use xacro or urdf files from the previous package: navvis_description. It must be true if use_xacro_new is true. 
## Note
Package navvis_description is required for this package. Both package should be placed under /src

