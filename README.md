# shell_script_to_restore_from_External_HDD_to_Internal_HDD

Shell script to restore. with this, you will clone your external hard disk drive to your internal hard disk drive.<br>
<br>
Copy and paste this script into USB stick.<br>
First: download and use clonezilla to process.<br>
Once finished, don't exit but go to command line.<br>
mount your USB stick.<br>
find the script and execute it.<br>
<br>
this script is for a debian bullseye linux distribution. It should work with another but not tested<br>
Here my configuration:<br>
5 partitions<br>
/dev/sda1 - EFI System - FAT (version 32 bit)<br>
/dev/sda2 - linux file system ext4 - label: root<br>
/dev/sda3 - linux file system ext4 - label: home<br>
/dev/sda4 - linux file system ext4 - label: others<br>
/dev/sda5 - swap linux<br>
<br>
Before executing the script: Open it with text editor Read, read, read (only french comments)<br>
<br>
there is no warranty and won't be responsible for anything<br>
<br>
you may use it as you want<br>
<br>
Regards<br>
Licence:<br>
Do what you want with it.
