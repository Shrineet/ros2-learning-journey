# ROS2 Learning Journey

My first ROS2 beginner project using Python.  

## Projects

- **Publisher Node** (`simple_publisher.py`) → publishes messages to `chatter` topic every second.  
- **Subscriber Node** (`simple_subscriber.py`) → subscribes to `chatter` topic and prints received messages.

## How to Run

```bash
source /opt/ros/humble/setup.bash
cd ~/ros_ws
colcon build
source install/setup.bash
ros2 run my_first_pkg simple_publisher
ros2 run my_first_pkg simple_subscriber
