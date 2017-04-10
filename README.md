#Setup zsh  
apt-get install zsh
apt-get install git-core
wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh
chsh -s `which zsh`
sudo shutdown -r 0

#i3 dep
sudo apt install i3
sudo apt-get install i3blocks, scrot, imagemagick

#Login screen dep SDDM
sudo apt-add-repository ppa:blue-shell/sddm 
sudo apt-get install sddm 

#switch back 
sudo dpkg-reconfigure lightdm

#resources
https://realpython.com/blog/python/setting-up-sublime-text-3-for-full-stack-python-development/

#setup dynamic display switching https://help.ubuntu.com/community/DynamicMultiMonitor