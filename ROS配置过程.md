#配置ROS过程
	14353077 韩泽华

1.sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

2.sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 0xB01FA116

3.sudo apt-get update

4.sudo apt-get install ros-jade-desktop-full

5.apt-cache search ros-jade

6.sudo rosdep init

7.rosdep update

8.echo "source /opt/ros/jade/setup.bash" >> ~/.bashrc
source ~/.bashrc

9.source /opt/ros/jade/setup.bash

10.sudo apt-get install python-rosinstall
	
	经过以上步骤可配置成功ROS。ROS（Robot Operating System，下文简称“ROS”）是一个适用于机器人的开源的元操作系统，它能为异质计算机集群提供类似操作系统的功能。ROS 的主要目标是为机器人研究和开发提供代码复用的支持。