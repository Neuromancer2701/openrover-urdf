# openrover-urdf

This package contains the URDF for the OpenRover robot.

## Building

To build this package, run the following command from the root of your workspace:

```bash
colcon build --packages-select open_rover_model
```

## Usage

To view the robot model in RViz, first source your workspace, then run the following command:

```bash
. install/setup.bash
ros2 launch open_rover_model view_robot.launch.py
```