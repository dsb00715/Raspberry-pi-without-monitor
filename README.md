# Raspberry-pi-without-monitor
Connect Raspberry pi for the first time without monitor. All you need is just a pi, memory card, Internet and Router.

First Follow the procedure mentioned here: https://www.raspberrypi.org/documentation/installation/installing-images/

Once done, create an empty text file in the root directory of the SD card. Open CMD in windows as an Administrator,

F:
cd \
echo "foo" > ssh.txt
exit

now type "ipconfig /displaydns" in the command prompt

and Check the ip Address like shown in the attached image.

Now Open Putty and Login to the Raspberry pi as default username and password(pi and raspberry)

Run commands:
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install xrdp
