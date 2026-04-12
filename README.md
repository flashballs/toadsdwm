install guide

first install some dependincys
on arch this will be 
sudo pacman -S base-devel libx11 libxft libxinerama git
next
git clone https://github.com/flashballs/toadsdwm
then
cd ~/toadsdwm && chmod +x install.sh

now run
./install.sh

now opitanally 
you can run the installbonus.sh script wich
will give you a nord theme .Xresources and a .xinitrc
you can run this by running cd ~/toadsdwm && chmod +x installbonus.sh && ./installbonus.sh

i highly recomend not using a display manager so you can use startx
to start other programs if you run the installbonus script to get
my xinitrc file it will start picom, slstatus, and it has feh comment wich you can uncomment and
chnage it to point at you image file to get a wallpaper
optinal dependincys
sudo pacman -s feh picom rxvt-unicode

if you dont wanna use rxvt-unicode as your terminal you can change you tetminal
by editing the ~/toadsdwm/dwm/config.h and changing urxvt to you favorite terminal emulator ex xterm

