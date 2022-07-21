# Task-1-2-AI 

# Task1 install ubuntu and ROS 
# step1
Download VirtualBox VM 
# step 2
Download Ubuntu 20.04
# step3
see the system requirements and open ubuntu on virtualbox 
# step 4
copying the command and pasting into the ubuntu terminal

https://docs.ros.org/en/foxy/Installation.html


# task 2 , XUbuntu and ROS Installation on jetson nano 
# step1
Download XUbuntu 20.04 focal fossa L4T R32.3.1
# step 2 
using (etcher).. flash image on micro sd card 
# step 3
we have twe cases 
jetson nano A02 or B01

A02

we should plug in the SD card , Then we start the XUbuntu installation process 

B01

There is an important point before installation. We press a file in the SD card called extlinux.conf and open it in Terminal and enter the command  

`sudo vim extlinux.conf`

AND

`boot/tegra210-p3448-0000-p3449-0000-b00.dtb`

save file

finally plug in the SD card , Then we start the XUbuntu installation process 
# step4
install ROS 2 Foxy Fitzroy 

 https://docs.ros.org/en/foxy/Installation.html
 
Copying the commands through this link
