# anman_sensors
Collect sensors and actuators for robots. [URDF, XACRO, GAZEBO]

## View models
You can view each model with the following command:
```
roslaunch anman_sensors view_sensor.launch:=SENSOR_NAME
```
Example:
```
roslaunch anman_sensors view_sensor.launch:=rplidar_s1
```

## Sensors

* [ ] Intel realsense D435
* [x] IMU MPU9250
* [x] Lidar YDLidar G4

## Actuators

* [ ] Brushless DC Motor Hoverboard 6.5"
