# rm


This works with ROS Foxy

Create a new directory, for example "rm". Create inside the files src/robominer and introduce these 2 files inside the file named robominer.

Build and install:

cd ~/rm

colcon build

To launch the robot, go to the robot directory:

cd ~/rm/src/robominer/robominer_ign/robot

Launch the robot:

ign gazebo robot.sdf

To launch the cave, go to the cave directory:

cd ~/rm/src/robominer/robominer_ign/cave

Launch the cave:

ign gazebo cave.sdf


Launch the robot in the cave:

It does not work yet, I'm working on the launch file: launch.ign
