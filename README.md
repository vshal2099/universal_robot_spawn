1. clone this repo into src ros2 workspace:
git clone --recurse-submodules https://github.com/vshal2099/universal_robot_spawn.git

2. Do colcon build and source your workspace
   
3. launch gazebo and rviz:

"ros2 launch ur_simulation_gz ur_sim_control.launch.py ur_type:=ur30"

4 change robot use argument:  ur_type:=ur30 to desired model
