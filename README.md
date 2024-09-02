# ROS Resources

This is a community-compiled list of useful resources for robotics (with a focus on ROS). I make no guarantees on the quality of any of these resources. If you'd like to add something to the list, please submit a PR!
## Command ROS2
| ROS2 | DOCKER |
| ---- |
| colcon build --symlink-install | docker ps |
| source /opt/ros/humble/setup.bash | docker exec -it 2b79bd3b87dc bash |
| ros2 run tf2_tools view_frames | docker run --name container_name -e DISPLAY=host.docker.internal:0.0 -it image_name |
| ros2 run teleop_twist_keyboard teleop_twist_keyboard |
| ros2 run rviz2 rviz2 -d /root/ros2_ws/src/robot/rviz/nav2.rviz |
| ros2 launch nav2_bringup navigation_launch.py |
| ros2 launch slam_toolbox online_async_launch.py |

## ROS-Oriented

| Name | Links | Notes |
| ---- | ----- | ----- |
| Official ROS 2 tutorials/docs | [Docs](https://docs.ros.org/en/humble/) \| [Tutorials](https://docs.ros.org/en/humble/Tutorials.html) | ROS 2 |
| Official ROS Wiki | [Wiki](http://wiki.ros.org/Documentation) | ROS oriented but still useful for ROS 2 |
| Official ROS Index | [Index](https://index.ros.org/) | Complete list of packages and their documentation for ROS and ROS 2 |
| Official API Docs | [rclcpp](https://docs.ros2.org/latest/api/rclcpp/) \| [rclpy galactic](https://docs.ros2.org/galactic/api/rclpy/api.html) | |
| Articulated Robotics | [Blog](https://articulatedrobotics.xyz/) \| [YouTube](https://www.youtube.com/c/ArticulatedRobotics) \| [Forum](https://discourse.articulatedrobotics.xyz/) | ROS 2 Tutorials *(Disclaimer - this is me!)* |
| The Robotics Back-End | [Homepage](https://roboticsbackend.com/) | ROS, ROS 2, and general robotics |
| Automatic Addison | [Homepage](https://automaticaddison.com/) | ROS 2 and general robotics |
| The Construct | [Homepage](https://www.theconstructsim.com/) | ROS, ROS 2, and general robotics |
| Linobot robot | [Homepage](https://linorobot.org/) | ROS |
| Soft Illusion | [YouTube](https://www.youtube.com/@coolrobotics/) | |
| Tiziano Fiorenzani | [YouTube](https://www.youtube.com/@prandtlmayer) \| [Homepage](https://tiziano-school.thinkific.com/) | ROS |
| Hummingbird | [YouTube](https://www.youtube.com/@hummingbird19) | ROS 2 |


## Non-ROS
| Name | Links | Notes |
| ---- | ----- | ----- |
| Learn OpenCV | [Homepage](https://learnopencv.com/) | OpenCV |
| Nicolai Nielsen | [YouTube](https://www.youtube.com/@NicolaiNielsenAI) | Open3D, OpenCV |
