### SETUP INSTRUCTIONS

 - Install I3 Gaps. Do not install I3 first

#### Install polybar.

 - Install fonts for polybar - https://github.com/polybar/polybar/wiki/Fonts

 - https://itsfoss.com/install-fonts-ubuntu/

 - Install unifont with sudo apt-get install unifont

 - Install font Dina - https://medium.com/@vando/install-dina-font-on-debian-cb352b569c7c

```
wget -O Dina.zip 'https://www.dcmembers.com/jibsen/download/61/?wpdmdl=61&refresh=5b7193954297c1534170005'
unzip -d /usr/share/fonts/Dina Dina.zip
cd /usr/share/fonts/Dina/BDF
mkfontscale
mkfontdir
dpkg-reconfigure fontconfig-config
fc-cache -f
```
 - Install Siji font - https://github.com/stark/siji
 - After installing refersh font cache using fc-cache -f -v
 - Check if fonts are installed using fc-list or font-manager
 - Update the correct font names and families in polybar config using fc-list : family | grep Siji
 - Links - https://github.com/polybar/polybar/issues/313

#### Bluetooth
 - Install blueman and use the applet for bluetooth


