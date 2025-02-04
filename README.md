## Deep Pose Estimation from 3D Point Clouds


This work introduces a deep neural network to predict relative poses between two sets of 3D point clouds from RGBD camera or LiDAR scans. It aims to improve upon traditional point cloud registration methods like Iterative Closest Point (ICP) by addressing two main challenges: sensitivity to initialization and the high computational cost of successive data alignment and optimization steps.

The approach frames the problem as a pose regression task. The network is trained end-to-end, beginning with extracting point clouds from RGBD camera data. The architecture includes a PointNet backbone for feature extraction, followed by a multi-layer perceptron (MLP) and a final regression layer. This design aims to offer a more efficient and robust alternative to ICP for point cloud registration.

Check out the .pdf report file, which outlines in detail the work mentioned above.
