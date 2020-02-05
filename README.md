# AnsoniaClock
bash script for a 1898 Ansonia table clock ticks and chimes.

REQUIRES:
ogg123
cron

INSTRUCTIONS:
1. Download, untar the AnsoniaClock.tgz file, cd into the newly created AnsoniaClock directory.
2. Make sure AnsoniaClock.sh is executable.
3. Open the AnsoniaClock.sh file in a text editor and copy the example crontab line into your crontab.  Adjust the path to this directory.

3a. OPTIONAL: If you do not want to hear the constant 'ticks' comment out the last line of AnsoniaClock.sh.

You can start the script immediately with ./AnsoniaClock.sh

-or-

You can wait for cron to start it on the next hour or half hour.
