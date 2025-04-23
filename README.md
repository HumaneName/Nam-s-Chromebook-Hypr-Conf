# Nam-s-Chromebook-Hypr-Conf
### This config is based on Arch Linux and Hyprland!

## Requirements:
  Hyprland,
  Alacritty,
  wlogout,
  nautilus,
  hyprshot,
  HyprPanel,
  yay (AUR Helper),
  swww,
  PyWal,
  Matugen,
  flatpak,

  # Installation

### If you do not have a AUR helper such as Yay installed, please do so before running the install command!
[Sample Guide;](https://itsfoss.com/install-yay-arch-linux/)

Backup previous config
```
cp ~/.config/hypr/hyprland.conf ~/.config/hypr/hyprland.conf.backup
```

Install dependancies
```
yay -S --needed alacritty flatpak hyprland wlogout nautilus hyprshot hyprpanel swww pywal matugen && flatpak install app.zen_browser.zen
```

Replace current config with Nam's Chromebook Config
```
curl -o hyprland.conf https://raw.githubusercontent.com/HumaneName/Nam-s-Chromebook-Hypr-Conf
mv hyprland.conf ~/.config/hypr/hyprland.conf
```

# Post Installation

## Keybinds:
> Super + A; Alacritty (terminal)

> Super + Q; close active window

> Super + M; wlogout

> Super + E; File Manager

> Super + D; Browser

> Super + V; toggle floating window

> Super + Space; app launcher

> Super + Shift + S; screenshot square region

> Super + Shift + W; screenshot window

> Super + Shift + X; screenshot whole screen

> Super + F; fullscreen active

> Super + S; Special Workspace
