cmake_minimum_required(VERSION 3.5)
project(mini_pupper_description)

find_package(ament_cmake REQUIRED COMPONENTS)

ament_package()

install(DIRECTORY meshes launch urdf rviz config
  DESTINATION share/${PROJECT_NAME}
)
