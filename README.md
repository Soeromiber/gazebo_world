# gazebo_world
## How to World in Gazebo
- Copy the temp_world folder to ```~/PX4-Autopilot/Tools/sitl_gazebo/models ```
- Copy the template.world to ```~/PX4-Autopilot/Tools/sitl_gazebo/worlds ```
- Add the world name in ```~/PX4-Autopilot/platforms/posix/cmake/sitl_target.cmake``` in line set worlds
- Launch the world ``` gazebo  ~/PX4-Autopilot/Tools/sitl_gazebo/worlds/template.worlds```
