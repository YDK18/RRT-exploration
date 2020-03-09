# RRT-exploration

## Install ROS Kinetic package

> sudo apt-get update && sudo apt-get upgrade

> sudo apt-get install ros-kinetic-librealsense ros-kinetic-turtlebot ros-kinetic-turtlebot-apps ros-kinetic-turtlebot-interactions ros-kinetic-turtlebot-simulator

## 실행 순서

1. 예제 gazebo와 rviz 실행 (navigation 실행)

> roslaunch rrt_exploration_tutorials single_simulated_house.launch 

2. single launch파일 실행 -> publish point를 이용한 탐색 실행

> roslaunch rrt_exploration single.launch

실행시 주의 사항 - 순서를 정확하게 입력해줘야함.

![publish point 순서](https://github.com/YDK18/RRT-exploration/blob/master/sequence_of_points.png)

RRT exploration 실행 결과

![RRT exploration](https://github.com/YDK18/RRT-exploration/blob/master/rrt_exploration.png)
