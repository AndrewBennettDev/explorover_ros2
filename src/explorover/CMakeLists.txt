cmake_minimum_required(VERSION 3.5)
project(explorover)

find_package(ament_cmake REQUIRED)

# Add your dependencies here

# Add the executable
add_executable(robot_node src/nodes/robot_node.cpp src/robot_controller.cpp src/camera_handler.cpp src/ultrasonic_handler.cpp)

# Add any additional libraries or dependencies

ament_package()
