# linuxnotes
Notes for Linux

#### first setup
apt-get update
apt-get upgrade
apt-get install mariadb-server mariadb-client php-fpm nginx 

#### edit files in notepad:
nano filename
gedit filename

#### file with links/sources used with apt-get install:
/etc/apt/sources.list

#### disable swap file usage:
nano /etc/dphys-swapfile

find and set: CONF_SWAPSIZE=0
