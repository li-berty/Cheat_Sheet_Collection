## Resetting the root password in Linux
| Description | Command |
| :--- | :--- |
| Start the system, go to the boot menu (grub) and  to edit press | key "e"|
| Add the parameter to the end of the line beginning with linux| single init=/bin/bash |
| Boot into the root shell system | press Ctrl-X |
| Run the command to mount the root partition in read/write mode | mount -o remount,rw / |
| Run the command to change the root password | passwd root |
| Reboot the computer | reboot -f |
