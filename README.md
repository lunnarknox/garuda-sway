![Image](https://github.com/user-attachments/assets/1b94b030-4ad2-4b49-a531-bf5678b47f9f)

<h1 align="center"> Lunnar's Garuda Linux Dotfiles </h1>



## Wiki 📖

For more details and a comprehensive guide on using these dotfiles, check out the wiki. If you run into any issues accessing it (since it's self-hosted), let me know.

Ready to get started?

Download : [Garuda Download](https://garudalinux.org/editions)

You can also use the github wiki : [Github Wiki Link](https://github.com/yurihikari/garuda-hyprdots/wiki)

## About ❓
This is a customized mix of Yurihikari themes, optimized for dyslexia-friendly reading and adapted for the personal use of Remi Lunnar.

The aim of this repository is to provide a simple and easy to use ricing for Garuda Linux Sway and Hyprland. This was made before the official Garuda Linux Hyprland/Sway release.


## Additional features 👍
- Waybar themes switch (The main setup I use is intentionally minimalist to help with my dyslexia, making everything cleaner and easier to navigate. However, you still get access to all official repository themes, including the Waybar themes switch.)
- Background switch using Meta+Shift+b. (Backgrounds must be in the ~/.config/backgrounds folder)
- Easily add musics to mpd with the mpd_update function ( Assuming your musics are in ~/Music )

## Important Dependencies ⚠️
I use some apps not pre-included in the default Garuda Linux desktop. Please install them before using my dotfiles
to avoid any potential graphical issues.
- swaylock-effects (https://github.com/mortie/swaylock-effects)
- hyprlock-git
- rofi-wayland (https://github.com/lbonn/rofi) *using wofi by default on sway*
- waybar
- fastfetch
- cava-git
- foot
- hyprland (optional, if you don't want to use it, just remove the hypr folder)
- mpd
- mpc
- rose-pine-cursor
- rose-pine-hyprcursor
- ttf-font-awesome
- nerd-fonts (I installed them all by default)
- hyprpicker
- pipewire (who still uses pulseaudio on a wayland setup ?)
- wireplumber
- nwg-launchers
- mako
- most
- pavucontrol
- swayfx (if you just want sway, comment the swayfx line in the sway/config file)
- bluez
- bluez-utils
- grimblast
- gpu-screen-recorder
- btop
- networkmanager
- matugen
- wl-clipboard
- swww
- dart-sass
- brightnessctl
- gnome-bluetooth-3.0
- aylurs-gtk-shell
- micro
- blueberry
- kitty

Dependency List :
```bash
paru -S swaylock-effects hyprlock-git rofi-wayland waybar fastfetch cava-git foot hyprland-git mpd mpc rose-pine-cursor rose-pine-hyprcursor ttf-font-awesome nerd-fonts hyprpicker pipewire wireplumber nwg-launchers mako most pavucontrol swayfx bluez bluez-utils grimblast gpu-screen-recorder btop networkmanager matugen wl-clipboard swww dart-sass brightnessctl gnome-bluetooth-3.0 aylurs-gtk-shell micro blueberry kitty
```

**I didn't include personal apps like Youtube Music, Discord, VSCode and themes used in Brave etc. I can start adding them if more people ask me to.**

## Installation 🔧
### Ctrl+C Ctrl+V 😏
You'll need to install the dependencies yourself.
After you installed the dependencies (some may be missing depending of your distro), just clone the repository and copy/paste the files in the .config directory :

*Example* :
```bash
git clone https://github.com/lunnarknox/garuda-sway-config.git
cp -r garuda-sway-config/* ~/.config
```

Or simply pick what you need from the files, and use it in your own.

For the nwgbar icons, you can use the included script to install them (install.sh inside the nwgbar-icons folder)

Reboot and enjoy.

### Install Script ✈️
**Disclaimer** : This was only tested on fresh Garuda Linux installs and EndeavorOs using community sway edition. I am not responsible for any damage the script may cause, even though it's unlikely.
Run the **install.sh** script located at the root of the repository directory to install the dotfiles and its dependencies.

```bash
git clone https://github.com/lunnarknox/garuda-sway-config.git
cd ./garuda-sway-config
./install.sh
# You'll have some interactions sometime, it's not fully automatized
```

Reboot and enjoy.

This will work assuming you already have a working Desktop Environment. If you don't, make sure you install Sway/Hyprland first using official methods. I'll probably make a script to install Sway/Hyprland and the dotfiles on barebones Arch Linux Distro based installs later if I have the time.

Feel free to contribute and make a pull request if you want to add something to the script, or create your own script.

## Keybinds ⌨️

### Hyprland
Please, refer to this file : [Hyprland Cheatsheet](https://dotfiledocs.lightcrimson.com/en/keybinds)
Or use Meta+Shift+I to get a keybind sheet directly on your terminal.

## Waybar 📊
Swap between each version of the waybar using the paintbrush icon on the bar.
Shortcut is unavailable in Hyprland for now.

### Minimal Bar ⬜
![Image](https://github.com/user-attachments/assets/2c4a385a-8701-45ef-8f43-791f1cf6ef48)

## Colors 🖌️
I'm using primarly Black Catppuccin Macchiato as my color palette or Coolors.co black suggestion. They also have lot of themes and tutorials
to install their theme and color palette into your favorite apps.
https://github.com/catppuccin
https://coolors.co/


## Background Image 🖼️
DEFAULT : Using mainly March 7th or Total Black Wallpaper
https://www.pixiv.net/en/artworks/97911234 ( Artist : Rafa )
https://52kards.com/shop2/1920x1080-black-solid-color-background/ ( Artist : Unkown )

Put in the ~/.config/backgrounds whatever background you want, and do Meta+Shift+b to switch between backgrounds.

## Notice 📓
I am using **Garuda Linux Sway** as my distro. Depending on your system, some stuff may not work or break.
Please be aware of that before starting using my dotfiles.

This is a fork of the original project, and as such, it contains some divergences from the main repository. Certain files have been intentionally omitted due to risk management and compliance requirements specific to this work. Please note that this is a work in constant progress, and elements may undergo significant changes based on my preferences or evolving needs. I will create separate branches if major modifications to the current files are necessary, allowing you to track and access previous versions of the work.

I am not affiliated in any way to the official Garuda Linux Team. This is a personal ricing using Garuda Linux Sway as the main distro.

## Overview of Hyprland background
 🖼️
![Screenshot_2024-10-07-23-36-37_](https://github.com/user-attachments/assets/51481283-3d84-495a-8844-76d381acdd84)



## Special Thanks 🙏

- [LightCrimson](https://github.com/yurihikari) for the amazing base config.
- [Hyprpanel (Jas-SinghFSU)](https://github.com/Jas-SinghFSU/HyprPanel) for the AGS config.
- [Archcraft](https://archcraft.io/) for the base Hyprland config and inspiration.
- [Catppuccin](https://github.com/catppuccin/catppuccin) for their amazing color palette.
- [Understood](https://github.com/catppuccin/catppuccin) Thank you for the practical tips on how to manage dyslexia!

