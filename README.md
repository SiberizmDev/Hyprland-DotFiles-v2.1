# Dotfiles Install

```
git clone
```

Copy everything in `Hyprland Dotfiles v2.1` and put it in `/home/user/`

# Required Softwares

```
[Arch Linux]
yay -S hyprland waybar grimblast gdm brightnessctl playerctl swaylock-effects pamixer rofi-power-menu rofi-search-git wf-recorder btop htop pamixer zsh oh-my-zsh oh-my-zsh-powerline-theme-git ark unrar zip unzip pavucontrol xdg-desktop-portal-wlr neovim vim nano git wget hyprpaper swaybg dunst dolphin kvantum kate appimagelauncher-bin noto-fonts-emoji wl-clipboard xfce4-appfinder wofi ksysguard catfish firefox kitty polkit-gnome gnome-keyring ntfs-3g cliphist qt5ct lxappearance tesseract-data-tur tesseract-data-eng tesseract-data-rus
```

# Optional Softwares

```
[Arch Linux]
yay -S visual-studio-code-bin spicetify-cli jdk-openjdk jdk17-openjd jdk11-openjdk jdk8-openjdk disord bitwarden authy flatpak inkscape konsole neofetch github-desktop-bin webapp-manager steam virt-manager qemu-desktop dnsmasq iptables-nft go yarn npm python-pip

[All Distros]
flatpak install stremio flatseal obsproject atom
```

# Change Flatpak Apps Theme

```
sudo flatpak override --filesystem=$HOME/.themes
sudo flatpak override --filesystem=$HOME/.icons
sudo flatpak override --env=GTK_THEME=Sweet-Ambar-Blue-GTK
sudo flatpak override --env=ICON_THEME=Dracula
```

# Change System Theme

This process is required to activate qt5ct in the system and to apply the GTK Theme. We can start editing the environment side by typing the command `sudo nano /etc/environment`

```
...
GTK_THEME=Sweet-Ambar-Blue-GTK
QT_QPA_PLATFORMTHEME=qt5ct
...
```

# Change Shell

```
sudo chsh -s $(which zsh)
chsh -s $(which zsh)
```

# Screenshot

![[SS.png]]