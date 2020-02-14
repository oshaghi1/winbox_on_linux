# Install and Use Mikrotik winbox on Linux Desktops
This is the simple script to install and have  Mikrotik Winbox in the Linux Desktop



```
git clone git://github.com/oshaghi1/winbox_on_linux.git
cd winbox_on_linux
chmod a+x install
./install

```

You should have installed Wine on your linux before installing this.



To update the winbox, download the latest from the link blow and replace it with this file : /usr/bin/winbox.exe
https://mikrotik.com/download

OR
could just run this command :
```
# 64 bit
sudo wget -q https://download.mikrotik.com/winbox/3.21/winbox64.exe -O /usr/bin/winbox.exe
```
OR
```
# 32 bit
sudo wget -q https://download.mikrotik.com/winbox/3.21/winbox32.exe -O /usr/bin/winbox.exe

```
