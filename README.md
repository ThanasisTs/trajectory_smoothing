# The trajectory smoothing package
A ROS package for smoothing cartesian trajectories

## Description
* `trajectory_smoothing_server.py`: A server for smoothing a trajectory using Bezier curves. It accepts three vectors containing the x, y, z coordinates in the form of a service request and returns the corresponding Bezier curve in the form of a service response. The declaration of the services are [here](https://github.com/ThanasisTs/trajectory_smoothing/tree/main/srv).
* `Smoothing.srv`: Declaration of the service.

## Launch
`roslaunch trajectory_smoothing trajectory_smoothing.launch`

In the following plot, orange points correspond to raw trajectory data and blue points to the smoothed trajectory produced by the `trajectory_smoothing_server`.

<img src="https://github.com/ThanasisTs/trajectory_smoothing/blob/main/raw_smooth.png" width="1000">

