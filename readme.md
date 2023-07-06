# Description 
Using ROS make a chatroom for users where they can view and send messages that all users can see. Ensure that the chat room has at least 3 users/nodes that connect to the same.
## Ros Topic
The topic published amd subscribed is:
```sh
/chatroom
```
## Ros Message
```sh
string username
string chat
```

# Installation and Setup
* Ensure that you have Git and ROS (Robot Operating System) installed on your laptop. If you haven't installed them yet, please refer to the official documentation for instructions on how to install Git and ROS for your specific operating system
* Open a terminal or command prompt on your laptop.
* Create a catkin workspace and clone the cashier package
```sh
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
```
* Clone the repository by executing the following command:
```sh
git clone https://github.com/nimbusmustafa/ros-chatroom.git
```
* After the cloning process is complete, navigate to the workspace directory
```sh
cd ~/catkin_ws
```
* Make sure you have sourced your ROS workspace.
```sh
source devel/setup.bash
```
* Run catkin_make to build the ROS workspace and compile the packages
```sh
catkin_make
```
## Use
To run all the three nodes together
```sh
roslaunch chatroom launch.launch
```




# rqt graph
![Screenshot from 2023-02-01 19-07-59](https://user-images.githubusercontent.com/117943931/216240061-859acd70-69bd-41b5-8b47-2d452fae1af2.png)
# youtube link 
https://youtu.be/8aUIy2Tuo40
