# A Package for an Autonomous Car

## For every task, first start UC Bridge :
roslaunch pses_ucbridge pses_ucbridge.launch 

## Start Navigation Stack : 
roslaunch pses_navigation kai_configuration.launch
roslaunch pses_kinect_filter kinect_filter.launch
roslaunch pses_navigation move_base.launch
rosrun pses_control pses_trajectory

## Start Person following :
roslaunch pses_control personfollow.launch
