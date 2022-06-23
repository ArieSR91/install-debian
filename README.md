# Debian
Install Debian on Termux


$ termux-setup-storage\
$ apt install wget\
$ wget https://raw.githubusercontent.com/ArieSR91/install-debian/main/debian && chmod +x debian\
$ ./debian

#### After this operation complete you will automatically login to Debian as root
If you want to install Kali Linux on Debian\
type: \
root@debian~# ls\
install-kali\
root@debian~# chmod +x install-kali\
root@debian~# ./install-kali\
##### When you start termux you will be automatically login to Debian.

You can also login by typing:\
kali -u = login as user\
kali -r = login as root


To edit the username "nano ../usr/bin//kali"
### ------------------------------------------
## Kali Linux
After Debian is changed to Kali Linux\
do the update & upgrade command


follow this step to install Kali Linux GUI \
root@kali~# apt install xfce4 tigervnc-standalone-server dbus-x11


To login to vncviewer or Nethunter kex.\
vnc start = start vnc server\
vnc stop = stop vnc server


if you want to setting vnc \
root@kali~# nano /usr/local/bin/vnc \
rename (username) to your username

dont upgrade or install udisks2
