sudo dpkg --add-architecture armhf && sudo apt update

Copy the following lib files from the Pi4 firmware repository in folder /usr/lib

sudo systemctl start vncserver-x11-serviced.service

sudo systemctl enable vncserver-x11-serviced.service


sudo apt-get install openssh-server

sudo systemctl enable ssh

sudo service ssh restart

sudo systemctl start vncserver-virtuald
sudo systemctl enable vncserver-virtuald
