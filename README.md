# Car Simulation in Gazebo ROS
## Setup
Make a workspace folder named **car_simulator_ws**
```bash
mkdir -p car_simulator_ws/src
```
Paste the following files in the src folder:
* smb_control
* smb_description
* smb_gazebo
* teleop_twist_keyboard
<!-- -->
After pasting, go to the folder of the workspace (**car_simulator_ws**) and build the packages.
```bash
cd car_simulator_ws
catkin build
```
After building, source the **setup.bash** file present in the **devel** folder
```bash
source devel/setup.bash
```
## Launching the Simulator
After the setup, Launch the simulator by launching the launch file **simulate.launch** present in ***smb_gazebo*** using *roslaunch* command.
```bash
roslaunch smb_gazebo simulate.launch
```
After running, we would get:
* Rviz: For visualizing the Car/Robot, Values sent by Sensors present, etc
* Gazebo: For Simulating the Car/Robot
* Teleop Twist Keyboard: For controlling the Car/Robot using Keyboard
## Simulation
![SnT-Hackathon-2023-Robotics](https://github.com/Gill-Singh-A/SnT-Hackathon-23-Robotics/blob/master/assets/images/SnT-Hackathon-2023-Robotics.png?raw=true)
Simulation Video : [SnT-Hackathon-2023-Robotics](https://github.com/Gill-Singh-A/SnT-Hackathon-23-Robotics/blob/master/assets/videos/SnT_Hackathon_2023_Robotics.mp4)