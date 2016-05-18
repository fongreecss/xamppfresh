# Xamppfresh #
Installs the latest version of xampp(lampp) on your debian based os [Ubuntu tested]
###Current version 7.0.4####

####Prerequisites - if you don't already have them####
####1.) git ####
```sh
sudo apt-get install git
```
####2.) gksu####
```sh
sudo apt-get install gksu
```
#####Or all in one line #####
```sh
sudo apt-get install -y git gksu
```

###Installation###
```sh
git clone https://github.com/frasaleksander/xamppfresh.git ~/xamppfresh
```
```sh
chgrp $(whoami) -R ~/xamppfresh
```
```sh
~/xamppfresh/xamppfresh install
```
Follow instructions on terminal. 

###TODO###
- [x] Xampp security embeded in installation process
- [x] Run xampp on system startup
- [x] Run xampp from terminal everywhere (lampp <action>)
- [x] Add Xampp-Control-Panel Launcher
- [x] Auto detect installation (32 or 64bit)
