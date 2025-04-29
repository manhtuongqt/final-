Cài đặt: `sudo apt-get install ros-noetic-teleop-twist-keyboard`

Thứ tự chạy:
1. `roslaunch carlike gazebo.launch` (sửa bản đồ dòng 3)
2. `rosrun teleop_twist_keyboard teleop_twist_keyboard.py`
3. `chmod +x ~/catkin_ws/src/carlike/scripts/control.py`
4. `rosrun carlike control.py`
5. `roslaunch carlike gmapping.launch`
6. `roslaunch carlike rviz.launch`