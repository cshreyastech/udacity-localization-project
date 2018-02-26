## Project: Localization README
---
#### Steps to run udacity-bot
Open first terminal
catkin_make
source devel/setup.bash
roslaunch udacity_bot udacity_world.launch


Open second terminal
catkin_make
source devel/setup.bash
roslaunch udacity_bot amcl.launch


Open third terminal
catkin_make
source devel/setup.bash
rosrun udacity_bot navigation_goal


#### Steps to run shreyas-bot
Open first terminal 
catkin_make
source devel/setup.bash
roslaunch shreyas_bot shreyas_world.launch


Open second terminal
catkin_make
source devel/setup.bash
roslaunch shreyas_bot amcl.launch


Open third terminal
catkin_make
source devel/setup.bash
rosrun shreyas_bot navigation_goal