# Install-ros1-on-ubuntu 20.04

here we i will show you how to install Ros-1 on ubuntu 20.04 

Step1:
you need to download VirtualBox 
you can press the link:
https://www.virtualbox.org/wiki/Downloads![image](https://github.com/Sultan-Alghamdi94/Install-ros-on-ubuntu20.04/assets/174812257/74b2f777-d4cd-407b-9f7b-53cb55af3dbe)

Step 2:
now you need to download ubuntu 20.04 

you can used this link to download it :
https://releases.ubuntu.com/20.04/

and here is the step to do it:

![v1](https://github.com/Sultan-Alghamdi94/Install-ros-on-ubuntu20.04/assets/174812257/932e69e1-c137-455c-98e1-683274d4fd62)

![v2](https://github.com/Sultan-Alghamdi94/Install-ros-on-ubuntu20.04/assets/174812257/cce03bdf-86bd-4d8d-a330-e92c5d18c8ed)

![v3](https://github.com/Sultan-Alghamdi94/Install-ros-on-ubuntu20.04/assets/174812257/eb203459-1e58-4cee-9df2-d2775027c474)

![v4](https://github.com/Sultan-Alghamdi94/Install-ros-on-ubuntu20.04/assets/174812257/b8f7c6cd-91b7-4697-975c-d04a548095aa)

Step 3:
after you download the ubuntu 20.04 you need to open the Terminal on the ubuntu and start to write this lines:

1- sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

2-sudo apt install curl

![1](https://github.com/Sultan-Alghamdi94/Install-ros-on-ubuntu20.04/assets/174812257/4208731b-13b3-4049-81e2-13301e93b9c8)

3-curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -

4-sudo apt update

5-sudo apt install ros-noetic-desktop-full

![2](https://github.com/Sultan-Alghamdi94/Install-ros-on-ubuntu20.04/assets/174812257/7d505fe5-afef-413c-83cb-768858a390b6)


6-echo "source /opt/ros/noetic/setup.bash"

![3](https://github.com/Sultan-Alghamdi94/Install-ros-on-ubuntu20.04/assets/174812257/aaa8435d-103e-4b8d-a2e8-f88304fa1b00)

7- to make sure that the Ros1 is working:
write this line:

roscore
![4](https://github.com/Sultan-Alghamdi94/Install-ros-on-ubuntu20.04/assets/174812257/7f097fa7-36f2-49bf-ac63-40ccf631dac7)
