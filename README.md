# rootfsramdisk
Scripts to put your Linux (currently being developed for OpenRC based distros) rootfs into a tmpfs

How to set up your system (at this time tested with Funtoo Linux 1.4):

Read docs/README.

rfsrd - script to switch between RAM disk and non volatile storage on a running system via mdadm, using a container set up as a loop device inside a tmpfs.

Pay particular attention to the configuration part at the beginning of the file. The default parameters are set for my current development system.

I'm not responsible for data loss and/or bricked installations! Use at your own risk!
