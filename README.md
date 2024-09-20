cd ~/ws_urdf

colcon build --symlink-install

source ./install/setup.bash

ros2 launch urdf_test dislapy.launch.py

