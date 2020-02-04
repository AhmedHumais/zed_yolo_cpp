# Stereolabs ZED - YOLO 3D

This package lets you use [YOLO (v2 or v3)](http://pjreddie.com/darknet/yolo/), the deep learning object detector using the ZED stereo camera in Python 3 or C++.

The left image will be used to display the detected objects alongside the distance of each, using the ZED Depth.

<p align="center">
  <img src="preview.png" width=676 height=450>
</p>

## Prerequisites

- Windows 7 64bits or later, Ubuntu 18.04

- [ZED SDK 3.x](https://www.stereolabs.com/developers/) and its dependencies ([CUDA](https://developer.nvidia.com/cuda-downloads))
- run make in darknet folder to install darknet platform

## How to use YOLO 3D in C++ (Linux only)

use cmake to build then executable can be run as
./darknet_zed obj.names obj.cfg obj.weights [Optional]video.svo

## Using Docker

A DockerFile is provided in the [docker folder](./docker)
