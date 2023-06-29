# ROS2-turtlesim-colcon-build
~/ros2_humble/src/ros/ros_tutorials/turtlesim/src$ 에 있는 turtle_frame.cpp 파일을 열어서 setWindowTitle("TurtleSim");을 setWindowTitle("TurtleSim Moses");로 변경하고 저장.

~/ros2_humble/src/ros/ros_tutorials/turtlesim$ 에서 . ~/ros2_humble/install/local_setup.bash 소싱해 놓고

colcon build 실행.

![image](https://github.com/kutmslee/ROS2-turtlesim-colcon-build/assets/38107813/ae4c9eee-92fe-492f-a871-15bd460ea3e9)

~/ros2_humble/src/ros/ros_tutorials/turtlesim/build/turtlesim$ 에서 turtlesim_node 파일이 새로 빌드되어 현재 시간으로 갱신 됬는지 확인.

새로 빌드된 turtlesim_node 파일을 ~/ros2_humble/build/turtlesim 폴더로 복사. cp turtlesim_node ~/ros2_humble/build/turtlesim

ros2 run turtlesim turtlesim_node 실행.

![image](https://github.com/kutmslee/ROS2-turtlesim-colcon-build/assets/38107813/23d24fc9-df20-41fd-b5bd-6f70ea0d5418)

