# TOC
- Free course
- setup simulator
  - GNS3
- download ios images -> add to gns3
- config GNS3

# Courses
- Free CCNA: https://www.youtube.com/watch?v=H8W9oMNSuwo&list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ
  
# Setup simulator Step by step


## Setup GNS3
 <!-- https://docs.gns3.com/docs/getting-started/installation/linux/ -->

### Ubuntu
```sh
sudo add-apt-repository ppa:gns3/ppa
sudo apt update -y
sudo apt install gns3-gui gns3-server

sudo dpkg --add-architecture i386
sudo apt update -y
sudo apt install gns3-iou

sudo chmod 755 /usr/bin/ubridge
sudo ubridge libvirt kvm wireshark docker
```
### add images
1. download IOS images
2. add image to gns3
- Edit -> Preference > Dynamips -> IOS Routers -> New 
