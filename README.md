# pangolin_robot

# Login

CSL@TT

```
ssh pangolin@10.100.4.54
```

CSL-FET@TT

```
ssh pangolin@192.168.1.222
```

Password: csl92021164

# Bringup

```
cd ~/pangolin_ws/ && source install/setup.bash && ros2 launch pangolin_bringup pangolin_bringup.launch.py 
```

# Keyboard control

Control robot via robot/cmd_vel 
```
python ~/pangolin_ws/src/quadruped_robot_4_DOF/pangolin_control/pangolin_control/pangolin_keyboard.py 
```
