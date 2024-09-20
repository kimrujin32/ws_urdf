cd ~/ws_urdf
colcon build --symlink-install
source ./install/setup.bash
ros2 launch test_urdf dislapy.launch.py
