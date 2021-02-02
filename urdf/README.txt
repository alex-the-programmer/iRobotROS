Launching URDF:

xacro --inorder urdf/irobot.xacro > urdf/irobot.urdf && roslaunch urdf_tutorial display.launch model:=urdf/irobot.urdf