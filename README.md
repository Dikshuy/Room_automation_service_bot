## butler_bot

This robot will autonomously navigate to the location specified by the user.
After cloning this repo, do the following steps:

```bash
cd ~/catkin_ws/src
catkin_create_pkg Room_automation_service_bot rospy
cd ..
catkin build or catkin_make                   ## do any one of it
source devel/setup.bash
cd src/Room_automation_service_bot/
```
Now, your environment has been set up.

Write all these commands in different terminals:

```bash
roscore
```
```bash
roslaunch Room_automation_service_bot model.launch
```

Gazebo world will pop-up. This procedure may take some time.
```bash
rolaunch Room_automation_service_bot model_slam.launch
```

Now, you can do mapping in this world

