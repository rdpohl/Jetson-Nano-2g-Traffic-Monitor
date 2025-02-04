Author:      Richard D. Pohl\
Date:        February, 2025\
Description: From scratch installation of Jetson nano, 2g, software setup for python3 libraries, and installation of Traffic program, and instructions for use

#Step I:\
Download Jetson Nano softare for etching onto a Micro SD card. Use this link [Jetson Nano Developer](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#intro), and write to Micro SD card (16Gb in this case) using Balena Etcher. Load card into Jetson Nano and boot the computer.


Note: I am using a keyboard, mouse, and monitor to complete this initial step. While running the program, however, I will be running the Nano headless.

#Step II:\
Boot the Nano and go through the installation routine for Ubuntu. 

- After the initial installation run sudo apt update and sudo apt upgrade (accept/use the defaults when prompted)
- Before reboot:
- Install pip3, sudo apt install python3.pip
- Install jtop, sudo pip3 install -U jetson-stats
- Reboot 

#Step III:\
- Setup Docker from the Jetson Zoo
- Going to locate Docker image on external thumb drive


  
