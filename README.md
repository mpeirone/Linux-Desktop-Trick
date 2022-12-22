# Ubuntu-Trick

### Move show application on left:
```
gsettings set org.gnome.shell.extensions.dash-to-dock show-apps-at-top true
```
### Fix alx wake online:
https://github.com/AMV007/alx_dkms_installer (haojunyu pull request)

### Fix "popping sound":
https://askubuntu.com/questions/1230833/annoying-click-popping-sound-on-ubuntu-20-04
```
echo "options snd_hda_intel power_save=0" | sudo tee -a /etc/modprobe.d/audio_disable_powersave.conf
```
