# niitblue_cnoid_pkgs

cp niitblue_cnoid_turtle_bringup/misc/materials.yaml choreonoid/share/default/materials.yaml

bringup
$ niitblue_cnoid_turtle_bringup turtle_world2.launch

SLAM
$ roslaunch niitblue_cnoid_turtle_slam hector_turtle.launch

navigation
$ roslaunch niitblue_cnoid_turtle_navigation niitblue_turtle_navigation.launch
