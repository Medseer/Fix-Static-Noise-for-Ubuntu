To fix the noise from the background, copy the code below and enter to the terminal
"sudo nano /etc/modprobe.d/alsa-base.conf"
After entering the text editor, scroll down using arrow keys, at the bottom paste the code below
"options snd-hda-intel power_save=0 power_save_controller=N"
Enter a newline for good measure, then save the file by pressing "ctrl+o", then hit enter, after saving, reboot your computer