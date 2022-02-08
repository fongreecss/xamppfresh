# Xamppfresh #
Install the Xampp(Lampp) on Ubuntu (based OS)
###Latest version 7.0.6####

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

###Install###
```sh
git clone https://github.com/fongreecss/xamppfresh.git ~/xamppfresh
```

Install the latest version
```sh
~/xamppfresh/xamppfresh install
```
Install specific version
```sh
~/xamppfresh/xamppfresh install 7.0.6
```

###Uninstall###
```sh
~/xamppfresh/xamppfresh uninstall
```
Follow instructions on terminal. 

###TODO###
- [x] Xampp security embeded in installation process
- [x] Run xampp on system startup
- [x] Run xampp from terminal (lampp <action>)
- [x] Add Xampp-Control-Panel Launcher
- [x] Auto detect installation (32 or 64bit)
