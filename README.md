## Overview
The data in this repository is for the paper “Hand-eye Parameter Estimation Based on 3D Observation of A Single Marker”. It includes four sets of hand eye calibration data, i.e., single-marker data and pattern data in eye-in-hand configuration and in eye-to-base configuration. Please refer to the reference article for details.

## Setup

### eye-in-hand
``camera``: Intel Realsense D415;
``robot``: Jaka Zu7;
``target``: 4 × 6 ChArUco pattern or and 1 × 1 ChArUco

### eye-in-hand
``camera``: RVC-X mini
``robot``: Jaka Zu7
``target``: 4 × 6 ChArUco pattern or and 1 × 1 ChArUco

# The hand-eye calibration data
This data corresponds to the Case 1 in the following reference.

# Contributors
Dr. Yuxiang Sun http://eeyxsun.people.ust.hk/

Mr. Jin Wu http://www.jinwu.science

# Usage
There are 224 images along with the poses from robotic base to the end-effector. The users can first obtain the intrinsic paramters of the camera by method from Zhengyou Zhang 2000 and then compute the camera-chessboard transformation by PnP.

# Miscellaneous
The distance between two checkerboard squares in row or column is 30mm.

# Reference
Jin, G., Yu, X., Chen, Y., Li, J. (2023), Hand-eye Parameter Estimation Based on 3D Observation of A Single Marker, submitted to IEEE Trans. Instrum. Meas.
         
# Code
The  associated  codes can be downloaded on https://github.com/MatthewJin001/Single3D


