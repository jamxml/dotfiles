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
# screenshot
![image](https://github.com/user-attachments/assets/c7a03d1e-da75-4e20-9f16-c3299a5bc8ef)
# vs code theme 
doki wallpaper + doki gif sticker + material deepforest
![image](https://github.com/user-attachments/assets/e0fe92ec-cbe6-43a8-baa8-6e0a403c7600)

```
{
    "terminal.integrated.fontSize": 15,
    "editor.fontFamily": "JetBrains Mono",
    "editor.fontLigatures": true,
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Material Theme Deepforest",
    "doki.sticker.path": "/home/jam/Pictures/vscode-gif/emo.gif",
    "doki.sticker.css": "z-index:100;background-position:95% 80% ",
    "window.menuBarVisibility": "toggle",

}
```
