# rm


This works with ROS Foxy

Create a new directory, for example "rm". Create src/robominer/robominer_ign and introduce the 2 files inside the file named robominer_ign. Leave the ros_ign file aside and you should end up with 2 files: robominer_ign and ros_ign

Build and install:

cd ~/rm

colcon build

Launch the robot.

Go to the directory:

cd ~/rm/src/robominer/robominer_ign/robot

Launch the robot:

ign gazebo robot.sdf

Launch the cave:

cd ~/rm/src/robominer/robominer_ign/cave

Launch the robot:

ign gazebo cave.sdf


Launch the robot in the cave:

It does not work yet, I'm working on the launch file: launch.ign
