# interbotix_ws

roslaunch interbotix_xsarm_moveit xsarm_moveit.launch robot_model:=wx250 use_actual:=true dof:=5

roslaunch interbotix_xsarm_control xsarm_control.launch robot_model:=wx250
