Oh-My-Zsh
=========
This is how to get Oh-My-Zsh installed. I have also included my own
zshrc setup. This is a slightly different shell than bash but one I 
personally enjoy.

##Prereq:##

apt-get install zsh
apt-get install git-core

Getting zsh to work in ubuntu is weird, since sh does not understand the source command. So, you do this to install zsh

wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh

and then you change your shell to zsh

chsh -s `which zsh`

and then restart

sudo shutdown -r 0



