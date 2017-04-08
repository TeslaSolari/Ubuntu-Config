#i3 dep
sudo apt install i3
sudo apt-get install i3blocks, scrot, imagemagick

#Login screen dep SDDM
sudo apt-add-repository ppa:blue-shell/sddm 
sudo apt-get install sddm 

#Login screen dep Aether
sudo sh -c "echo 'deb http://download.opensuse.org/repositories/home:/antergos/xUbuntu_16.10/ /' > /etc/apt/sources.list.d/lightdm-webkit2-greeter.list"
sudo apt-get update
sudo apt-get install lightdm-webkit2-greeter
https://github.com/NoiSek/Aether#requirements

#switch back 
sudo dpkg-reconfigure lightdm

#resources
https://realpython.com/blog/python/setting-up-sublime-text-3-for-full-stack-python-development/