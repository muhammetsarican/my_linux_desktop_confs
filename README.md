# My Linux Desktop Configurations

I'm publishing my hyprland and waybar configurations.



## Screenshots

![App Screenshot](https://i.imgur.com/f3veigq.png)


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

Finally reboot your desktop. Congrats 🎉


## Dependencies for some functions work

```bash
hyprland
waybar
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
wlogout
pavucontrol
pulseaudio
gsimplecal
cherrytree
rofi-emoji
ttf-apple-emoji (AUR)
tesseract
hyprpicker-git (AUR)
xdg-user-dirs
dunst
```
## Some Solutions

If you get **EACCES Permission denied** warning at your waybar, you can run this code:
```bash
sudo usermod -aG input <user_name>
```
## Feedback

If you have any feedback, please reach out to us at [muhammetsarican.com](https://muhammetsarican.com/contact)


## Authors

- [@muhammetsarican](https://www.github.com/muhammetsarican)

