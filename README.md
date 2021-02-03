# arm_tutorial

## Please command
```
mkdir -p ~/ros_package/ur_ws/src
cd ~/ros_package/ur_ws/src
git clone https://github.com/tsuchidashinya/arm_tutorial
cd ..
rosdep update
rosdep install --from-paths src --ignore-src -r -y
catkin build

source ~/ros_package/ur_ws/devel/setup.bash
roslanch ur_gazebo ur3.launch
```
### Other terminal
```
python ~/ros_package/ur_ws/src/arm_tutorial/python_file/arm_control.py
```
