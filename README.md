# turtlebot3-melodic
all packages for turtlebot3 on melodic


## Clone repo
```linux
git clone https://github.com/bunchofcoders/turtlebot3-melodic.git

cd turtlebot3-melodic
```
## source ros/melodic
```linux
source /opt/ros/melodic/setup.bash
```
## build all packes
```linux
catkin_make
```
### we need set env variable for which flavor to use, there are other options like waffle etc. pls check turtlebot3 docs
```linux
export TURTLEBOT3_MODEL=burger

echo $TURTLEBOT3_MODEL 

roslaunch turtlebot3_gazebo turtlebot3_house.launch
```
If you have gazebo installed you should see gazebo and turtlebot in a room. You can use turtlebot_teleop to run the robot using keyboard
