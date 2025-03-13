cmake_minimum_required(VERSION 3.8)
project(rm_msgs)

find_package(rosidl_default_generators REQUIRED)
rosidl_generate_interfaces(${PROJECT_NAME}
        "msg/DataMCU.msg"
        "msg/DataRef.msg"
        "msg/DataAI.msg"
        "msg/Ps2Data.msg"
        "msg/GoalPose.msg"
        "msg/DataNav.msg"
)

ament_package()

