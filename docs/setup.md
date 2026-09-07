# Setup
1. I downloaded UTM and then downloaded UBUNTU 24.04 to match the ROS2 Jazzy 24.04 version that I would be using. ARM 64 Build because I am on APPLE silicon
2. I created a new virtual machine of LINUX in UTM
3. Set Locale to ensure UTF-8 text encoding
4. Add ROS2 apt repository so the system knows where to get ROS packages
5. Install ROS2 ros-jazzy-desktop which is the full version with GUI tools like RVIz
6. Verify ROS2 by with talkers and listeners
```
    ros2 run demo_nodes_cpp talker
    ros2 run demo_nodes_cpp listener
```