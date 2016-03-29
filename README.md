
Welcome to 301_linux. 

Your kit includes everything needed to get you up and running; after you've completed a stretch (jessie/sid) netinstall. Assuming you are at tty1

You will first notice, aside from this readme, a few folders(show hidden). 

1.openbox: This includes the scripting needed to start a featured openbox by issuing 'startx' at the tty1. 

2.tint2: This is your Panel that displays open programs and some icons for certain open programs. How you modify this is your choice. 

3..conkyrc: This is a light script that shows in the upper right-hand corner of your screen. It contains system properties and events you will find useful. 

_______________________________________________________________________________
If you are on a wired connection, you wont need to change a thing (aside from the optional /etc/network/interfaces configging).
Wifi: (as root) 'man iwconfig' and go from there. (wiki.debian.org is your friend)

Package List(not a complete list, deps will install automatically): 

(as root)
1.nano /etc/apt/sources.list 
(add at the bottom of the list): 
#sid  
deb http://ftp.debian.org/debian/ sid main contrib non-free
deb-src http://ftp.debiab.org/debian/ sid main contrib non-free
(perform apt-get update)

2.apt-get install
7kaa, abook, alsa-base, alsa-oss, alsa-utils, assword, cmake, cmatrix, conky, coreutils, debian-archive-keyring, dict, dpkg, feh, gawk, gcc, genius, glirc, gmrun, hasciicam, hdparm, htop, inxi, iw, iwconfig, jack, lm-sensors, mc, minetest, moc, mplayer, nano, ninvaders, openbox, openssl, pianobar, pulseaudio, rsync, rtorrent, screen, screenfetch, scrot, sl, speedtest-cli, stterm, suckless-tools, sudo, tint2, tor, torsocks, wget, xinit, xombrero, xorg, xserver-xorg, xtrlock, youtube-dl, zathura, zip

3.apt-get update
4.apt full-upgrade
_______________________________________________________________________________
Okay! it's almost ready. 

1.Place .xinitrc, .conkyrc and .xombrero.conf in /home/user
2.Place openbox and tint2 in /home/user/.config
3.Place woods.jpg in /home/user/Pictures
4.issue: startx (as regular user) 
5.Right click, nets, irc, /join #301 
_______________________________________________________________________________
This kit distro is based on Debian jessie/sid(stretch). The existance of the distro is based on the existance of the packages in the repositories of Debian. You will find we can not go extinct. 

Many of the packages chosen in the creation of this kit are CLI based and required a little getting used to, in most cases. You will find your system idles at a very small footprint; this is due to the very light nature of its design...

Installing bloat would be your endeavor alone. 
________________________________________________________________________________

Have a lot of fun! 

_________________________________________________________________________________
 
