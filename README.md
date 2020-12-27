# RaspberryPi400-setup
Debian on a Rapberry Pi 400


``fdisk -l #checking disks are correct size``

``apt update && apt upgrade``

``iwlist wlan0 scan #problem recognising WiFi``

# Prerequisites

apt-get install aptitude

aptitude install perl perl-doc

apt-get install wget

apt-get install keyboard-configuration

dpkg-reconfigure keyboard-configuuration

service keyboard-setup restart

apt-get install sudo

apt-get install git

   
# Vim

apt-get install vim

vim /etc/default/keyboard 


# LaTeX

wget "http://mirror.ctan.org/systems/texlive/tlnet/install-tl-unx.tar.gz"

tar -xzf install-tl-unx.tar.gz 

cd install-tl-20201225/

sudo ./install-tl 

dpkg-reconfigure locales

apt-get install locales

dpkg-reconfigure locales

cd

vim .bashrc

systemctl reboot

pdflatex --version

vim .bashrc

vim /etc/bash.bashrc


# R

sudo apt install dirmngr apt-transport-https ca-certificates software-properties-common gnupg2

sudo apt-key adv --keyserver keys.gnupg.net --recv-key 'E19F5F87128899B192B1A2C2AD5F960A256A04AF'

sudo add-apt-repository 'deb https://cloud.r-project.org/bin/linux/debian buster-cran35/'

sudo apt-get install curl libcurl4-openssl-dev libxml2-dev libssl-dev libgdal-dev libproj-dev xorg libx11-dev libglu1-mesa-dev libcairo2-dev libudunits2-dev libv8-dev libprotobuf-dev libjq-dev protobuf-compiler phantomjs r-base

R --version

sudo R

sudo systemctl status ssh

ip a

sudo adduser brian

usermod -aG sudo brian

cd /etc/ssh/

vim sshd_config 

history > history.sh
