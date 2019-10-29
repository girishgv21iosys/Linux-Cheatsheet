# Linux-Cheatsheet
#SNAP
snap changes
sudo snap abort #id
snap install appname --classic


#TLP
sudo add-apt-repository ppa:linrunner/tlp
sudo apt-get update
sudo apt-get install tlp tlp-rdw
sudo tlp start

sudo tlp-stat -b
              -s 


#SENSORS
sudo apt install lm-sensors


#ADD GROUP
sudo groupadd www
sudo chgrp -R www /opt/lampp/htdocs


#PUBLIC
sudo chmod -R 777 /opt/lampp/htdocs/
sudo chmod -R 755 /opt/lampp/htdocs/


#CACHE
sudo polipo -x
sudo find ~/.cache/ -type f -atime +365 -delete


#THEMES
Extract: tar xvf Sweet-*.tar.xz
	 tar xvzf Sweet-*.tar.gz
Move: sudo mv Sweet-* /usr/share/themes/
      sudo mv Sweet-* /usr/share/icons/	


#RUN
sudo ./manager-linux-x64.run
