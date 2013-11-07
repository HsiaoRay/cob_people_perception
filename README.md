Build Procedure
===============

Download the source for the dependency
`git clone https://github.com/ipa320/cob_perception_common.git`
Dowload the source for this code
`git clone https://github.com/ipa320/cob_people_perception.git`

Add your path to your `~/.bashrc`. For example, if you cloned the file into your home directory and make sure it's after the source declaration you made when you installed ROS:
`export ROS_PACKAGE_PATH=$ROS_PACKAGE_PATH:$HOME/cob_perception_common`

Then run CMake from within the directory you cloned
`mkdir build && cd build && cmake ..`

In the directory where you clone the files run `rosmake`

To Run
======
Please see the [wiki](http://wiki.ros.org/cob_people_detection).