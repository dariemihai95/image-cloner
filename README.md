# image-cloner
This describes how to clone an image from an sd card

sudo fdisk -l

sudo dd bs=4M if=/dev/sdc of=/home/user/image.img

if = source of = destination

for verboose use watch ls -latrh *.img in a separate window
