## Resetting the root password in Linux
| Action | Command |
| :--- | :--- |
| Start the system, go to the boot menu (grub) and press for editing | key "e"|
| Add the parameter to the end of the line beginning with linux| single init=/bin/bash |
| Boot into the root shell system | press Ctrl-X |
| Run the command to mount the root partition in read/write mode | mount -o remount, rw / |
| Run the command to change the root password | passwd root |
| Reboot the computer | reboot -f |
