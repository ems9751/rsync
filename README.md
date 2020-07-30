# rsync
simple bash script for syncing files between different drives
This script will create 2 directories /mnt/usb and /mnt/system
The script will automate the mount for both /dev/sda1 and /dev/sdb1 to the new directories created
The script will then automate rsync until finished and then umount the drives and reboot
