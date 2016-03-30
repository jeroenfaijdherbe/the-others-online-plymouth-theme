# Plymouth theme for The Others Online

wip


add to plymouth

```
sudo ln -s <pathtosrcfolder> /lib/plymouth/themes/too
sudo update-alternatives --install /lib/plymouth/themes/default.plymouth default.plymouth /lib/plymouth/themes/too/too.plymouth 100
sudo update-alternatives --config default.plymouth
sudo update-initramfs -u
```
