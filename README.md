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
### Kali Linux
Do update & upgrade


follow this step to install GUI \
$ apt install xfce4 tigervnc-standalone-server dbus-x11


After the installation process complete,\
first login to vncviewer or Nethunter kex. \


vnc-start = start vnc server
vnc-stop = stop vnc server


if you want to edit screen resolution \
$ nano /bin/vnc-start\
vncserver -geometry (your screen resolution)

After login to the vnc server,\
wait for the desktop to load and logout\
so that there are no error during installation\
Go back to the Debian CLI you changed to Kali on Termux


$ apt install 
