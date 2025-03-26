# ROS Packages for RealMan Robots

## 1. Package realman_description

> 功能：对RealMan RM65b进行运动学建模，并输出其模型描述urdf文件。<br>
> 启动：roslaunch realman_description realman_display.launch

## 2. Package realman_msgs

> 功能：针对Realman RM65b生成特定类型的消息格式(msg/srv/action)，为RealMan RM65b及其他设备提供特定的消息类型。<br>
> 启动：

## 3. Package realman_moveit

> 功能：使用moveit对RRealMan RM65b进行运动规划及仿真。<br>
> 启动：roslaunch realman_moveit demo.launch

## 4. Package realman_gazebo

> 功能：在gazebo中利用realman_control功能包对RealMan RM65b进行运动学及动力学仿真。<br>
> 启动：
>> (1)仿真：roslaunch realman_gazebo realman_gazebo_control.launch<br>
>> (2)真机：roslaunch realman_gazebo realman_bringup_moveit.launch

## 5. Package realman_driver

> 功能：通过以太网实现对RealMan RM65b真机的通讯及命令发送。<br>
> 启动：

## 6. Package realman_control

> 功能：配置通讯接口并根据指令进行控制真实RealMan RM65b机器人。<br>
> 启动：roslaunch realman_control realman_control.launch

## 7. Package realman_demo

> 功能：利用RealMan RM65b进行功能开发，并实现相应的demo。<br>
> 启动：
>> (1)机械臂按摩：roslaunch realman_demo massage_demo.launch
