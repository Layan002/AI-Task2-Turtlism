# Install ROS1 
Ensure you have ROS 1 installed on your system. If you haven't installed it yet, you can follow [the official ROS installation guide](http://wiki.ros.org/ROS/Installation).

# Install Turtlesim Package:
Make sure the Turtlesim package is installed. You can install it using the following command:
```
sudo apt-get install ros-noetic-turtlesim
```
> [!NOTE]
> Replace noetic with your ROS distribution if you're using a different version (e.g., melodic, kinetic).

# Initialize ROS:
Source your ROS setup file to set up the environment:
```
source /opt/ros/noetic/setup.bash
```
<img src= "https://github.com/user-attachments/assets/bca0d927-9473-488e-9cbb-665d02d715c7" alt= "image" width= 400>

# Start ROS Master:
Launch the ROS Master by running:
```
roscore
```
<img src= "https://github.com/user-attachments/assets/8184bfe2-27a6-4642-959c-d923a5cfd4bc" alt= "image" width= 400>

# Launch Turtlesim:
Open a new terminal, source the setup file, and launch Turtlesim:
```
source /opt/ros/noetic/setup.bash
rosrun turtlesim turtlesim_node
```

<img src= "https://github.com/user-attachments/assets/a5430c60-1a1d-4c06-9ace-a0f6298347cc" alt= "image" width= 700>

# Control the Turtle:
You can control the turtle using the turtle_teleop_key node. Open a new terminal, source the setup file, and run:
```
source /opt/ros/noetic/setup.bash
rosrun turtlesim turtle_teleop_key
```
> [!NOTE]
> Use the arrow keys to move the turtle around.

<img src= "https://github.com/user-attachments/assets/a07e8a1d-ac1b-409a-a3b6-7581268f1613" alt= "image" width= 400>

<img src= "https://github.com/user-attachments/assets/88362e2e-b0a8-49ff-9b65-47f3608dc4d3" alt= "image" width= 400>

## All windows
<img src= "https://github.com/user-attachments/assets/468b1835-9cc4-4a4e-bbe7-c7c43338c76a" alt= "image" width= 400>

<br>
<br>
<br>
This is for ROS1, for ROS2 follow the next steps:

# Install ROS 2:
Ensure you have ROS 2 installed on your system. If you haven't installed it yet, you can follow [the official ROS 2 installation guide](https://docs.ros.org/).

# Install Turtlesim Package:
Make sure the Turtlesim package is installed. You can install it using the following command:
```
sudo apt-get install ros-foxy-turtlesim

```
> [!NOTE]
> Replace foxy with your ROS 2 distribution if you're using a different version (e.g., galactic, humble).

# Source ROS 2 Setup:
Source your ROS 2 setup file to set up the environment:
```
source /opt/ros/foxy/setup.bash
```
> [!NOTE]
> You should unset ROS1 since it's still open unless otherwise you will get this error: <br>
> ![image](https://github.com/user-attachments/assets/92fe0ca9-9793-49c8-abe8-e0fb0cb23305)



# Launch Turtlesim:
Open a new terminal, source the setup file, and launch Turtlesim:
```
source /opt/ros/foxy/setup.bash
ros2 run turtlesim turtlesim_node
```








