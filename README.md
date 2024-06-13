# My Linux Desktop Configurations

I'm publishing my hyprland and waybar configurations.



## Screenshots

![App Screenshot](https://github.com/muhammetsarican/my_linux_desktop_confs/blob/main/project.png)


## Features

- Volume increase or decrease from topbar
- Brightness increase or decrease form topbar
- Workspaces can set for monitors
- You can create your own binds


## Run Locally

Clone the project

```bash
  git clone https://github.com/muhammetsarican/my_linux_desktop_confs.git
```

Go to the project directory

```bash
  cd my_linux_desktop_confs
```

Replace configuration files with yours

```bash
  mv . ~/.config/
```

At last, you have to define config file for ly display manager

```
  ly-dm --config ~/.config/ly/config.ini
```

Finally reboot your desktop. Congrats 🎉


## Dependencies for some functions work

```bash
hyprland
waybar
ly
hyprpaper
wl-clipboard
konsole
cliphist
blueman
rofi
grim
slurp
wireplumber
xsensors
btop
brightnessctl
wlogout-git
pavucontrol
pulseaudio
gsimplecal
cherrytree
rofi-emoji
noto-fonts-emoji
ttf-hack-nerd
tesseract
hyprpicker-git (AUR)
xdg-user-dirs
dunst
electron25
```
## Some Solutions

If you get **EACCES Permission denied** warning at your waybar, you can run this code:
```bash
sudo usermod -aG input <user_name>
```

If you not see icons on your terminal you can change the font to *Hack Nerd Font* or *MesloLGS NF*.

## Feedback

If you have any feedback, please reach out to us at [muhammetsarican.com](https://muhammetsarican.com/contact)


## Authors

- [@muhammetsarican](https://www.github.com/muhammetsarican)

