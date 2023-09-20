# SDF file for a Beaker

All necessary files required to spawn a semi transparent beaker in the gazebo environment integrated with ROS.

Model created using Blender 2.82

# How to Import?

Simply edit the lauch file for your gazebo environment by adding a new node with the appropriate path specified.

An example for this:

```
<node name="spawn_box" 
  pkg="gazebo_ros"
  type="spawn_model"
  args="-sdf -file <your path here> -model box -x <x value here> -y <y value here> -z <z value here>"
  respawn="false" 
  output="screen" />
```
