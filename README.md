# install this 
kitty,
firefox, 
rofi, 
yay, 
thunar, 
picom,
vim,
feh,
flameshot,
otf-san-francisco,
battery popup,
jet brains ttf, 
awesome font,
bumblebee-status,
mesa drivers,
auto-cpufreq,
stacer,
alternating-layouts-git.

# optimization 
```
yay -S minq-ananicy-git
sudo systemctl start ananicy.service
sudo systemctl enable ananicy.service

```
stacer + auto-cpufreq
## next tips
```
journalctl --vacuum-size=30M  

journalctl --verify
```
edit this
```
vim /etc/systemd/journald.conf
```
change this 
```
systemmaxuse=30M
systemmaxfilesize=20M
```
