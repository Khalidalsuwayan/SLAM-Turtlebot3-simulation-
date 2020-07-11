# SLAM-Turtlebot3-simulation- (ROS Kinetic)
### If you haven't downloaded Turtlebot3 packages you may find them in the link below
###### https://emanual.robotis.com/docs/en/platform/turtlebot3/pc_setup/
## In the beginning, we are gonna run Gazebo World in order to see the map
#### The used world is Turtlebot3 House and the used turtlebot model is burger.
```ruby
export TURTLEBOT3_MODEL=burger
```
```ruby
roslaunch turtlebot3_gazebo turtlebot3_house.launch
```
## In order to control a TurtleBot3 with a keyboard. Open new terminal.
```ruby
export TURTLEBOT3_MODEL=burger
```
```ruby
roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
```
## Thirdly, open new terminal and export the robot model and run the SLAM node in RViz.
```ruby
export TURTLEBOT3_MODEL=burger
```
```ruby
roslaunch turtlebot3_slam turtlebot3_slam.launch slam_methods:=gmapping
```
## Lastly


