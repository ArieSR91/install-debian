# Debian
Install Debian on Termux


$ apt install git\
$ git clone https://github.com/ArieSR91/install-debian \
$ cd install-debian\
$ chmod +x start\
$ ./start

#### After this operation complete you will automatically login to Debian as root
If you want to install Kali Linux on Debian\
type: \
$ ls\
$ chmod +x install-kali\
$ ./install-kali
##### The above process is to add Kali Linux repository and changed Debian to Kali Linux
### ------------------------------------------
## Kali Linux
After Debian is changed to Kali Linux\
do the update & upgrade command


follow this step to install Kali Linux GUI \
$ apt install xfce4 tigervnc-standalone-server dbus-x11


After the installation process complete,\
type:\
chmod +x /bin/vnc-start && chmod +x /bin/vnc-stop


To login to vncviewer or Nethunter kex.\
vnc-start = start vnc server\
vnc-stop = stop vnc server


if you want to edit screen resolution \
$ nano /bin/vnc-start\
vncserver -geometry (your screen resolution)
