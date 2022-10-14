# TOC
- setup GNS3
- download ios images -> add to gns3


# Step by step

## Ubuntu

### Setup GNS3
 <!-- https://docs.gns3.com/docs/getting-started/installation/linux/ -->
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
