LINUX_KERNEL
============

Kernel Hacking

cp /boot/config-3.2.0-64-generic .config
sudo make oldconfig
sudo make
sudo make modules
sudo make CONFIG_DEBUG_SECTION_MISMATCH=y
sudo make modules
ls
sudo make modules_install 
sudo make install
cd /boot/
sudo mkinitramfs -o initrd.img-3.9.0 
ls
sudo update-grub2
sudo reboot 
  
