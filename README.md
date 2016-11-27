# hello-world
Hello World!

This is a hello world for SlimJim, a Lenovo Thinkpad X1 Carbon. The goal is to provide a more-or-less reproducible backup-bootstrap solution for my environment, preferences, etc. pun intended.

2016-11-27
-----------------
Installed with the Debian LiveDVD image.

	Thinkpad X1 Carbon
	quaternian@slimjim.nowhere.network
	15G Swap on sda5
	30G root on sda6
	150G home on sda7

Installed VLC and some movies for watching

	# apt-get install vlc
	$ cp /media/Videos/* ~/Videos

Set up github and do hello-world walkthrough.
Clone me into ~/hello-world

	# apt-get install git
	$ git clone https://github.com/quaternian/hello-world.git
	
An install script should go here? Something like 

	$ cd hello-world && ./install.sh
