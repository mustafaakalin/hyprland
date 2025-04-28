[# hyprland](https://hyprland.org/

https://github.com/hyprland-community/awesome-hyprland

https://github.com/hyprwm/hyprland-plugins

```bash
pacman -S hyprland dunst pipewire wireplumber xdg-desktop-portal-hyprland polkit-kde-agent qt5-wayland qt6-wayland waybar rofi-wayland nwg-look brightnessctl mako uwsm hyprpaper hyprpicker hypridle hyprlock hyprcursor hyprsunset rofi-wayland flameshot wf-recorder obs-studio cliphist sddm xpad    
    
   

      
# polkit docs : https://wiki.hyprland.org/Hypr-Ecosystem/hyprpolkitagent/
# waybar wiki : https://github.com/Alexays/Waybar/wiki/Module:-Hyprland , https://wiki.hyprland.org/Useful-Utilities/Status-Bars/
# hyprland config : ~/.config/hypr/hyprland.conf

```

```bash

yay -S hyprland-workspaces hyprcursor-dracula-kde-git xcursor-pro-hyprcursor nordzy-hyprcursors sweet-cursors-hyprcursor-git swayosd-git hyprswitch sysboard wlogout swaylock-effects-git hyprls-git ddccontrol ddcutil eedid-tool libayatana-appindicator-glib-git        

```

```bash

# Language Bindings
go get -u github.com/thiagokokada/hyprland-go # https://github.com/thiagokokada/hyprland-go
# Hyprlang configuration tools
https://github.com/hyprland-community/hyprls # https://github.com/hyprland-community/hyprls

```

```bash

# Plugins
## split-monitor-workspaces # https://github.com/Duckonaut/split-monitor-workspaces
hyprpm add https://github.com/Duckonaut/split-monitor-workspaces # Add the plugin repository
hyprpm enable split-monitor-workspaces # Enable the plugin
hyprpm reload # Reload the plugins
### Add the following in your hyprland.conf file to automatically load the plugin at startup:
### exec-once = hyprpm reload -n
## hyprRiver https://github.com/zakk4223/hyprRiver
hyprpm add https://github.com/zakk4223/hyprRiver
# hyprpm enable hyprRiver
##  hyprNStack      https://github.com/zakk4223/hyprNStack
hyprpm add https://github.com/zakk4223/hyprNStack
### hyprpm enable hyprNStack
## hyprfocus https://github.com/pyt0xic/hyprfocus
hyprpm add https://github.com/pyt0xic/hyprfocus
## hyprland-dwindle-autogroup
hyprpm add https://github.com/ItsDrike/hyprland-dwindle-autogroup
### hyprpm enable dwindle-autogroup
## https://github.com/levnikmyskin/hyprland-virtual-desktops?tab=readme-ov-file#install
hyprpm add https://github.com/micha4w/Hypr-DarkWindow
### hyprpm enable Hypr-DarkWindow
### hyprpm reload
### hyprpm update
hyprpm add https://github.com/DreamMaoMao/hycov
### hyprpm enable hycov
hyprpm add https://github.com/KZDKM/Hyprspace
### hyprpm enable Hyprspace
hyprpm add https://github.com/zakk4223/hyprland-easymotion
### hyprpm enable hyprland-easymotion
hyprpm add https://github.com/virtcode/hypr-dynamic-cursors
### hyprpm enable dynamic-cursors
hyprpm add https://github.com/alexhulbert/Hyprchroma
### hyprpm enable hyprchroma

############# official plugins
# https://github.com/hyprwm/hyprland-plugins/tree/main/borders-plus-plus
# https://github.com/hyprwm/hyprland-plugins/tree/main/hyprbars
# https://github.com/hyprwm/hyprland-plugins/tree/main/hyprtrails
# https://github.com/hyprwm/hyprland-plugins/tree/main/csgo-vulkan-fix
# https://github.com/hyprwm/hyprland-plugins/tree/main/hyprwinwrap
# https://github.com/hyprwm/hyprland-plugins/tree/main/hyprexpo

## IPC plugins # https://hyprland-community.github.io/pyprland/

curl https://raw.githubusercontent.com/hyprland-community/pyprland/main/scripts/get-pypr | sh

# Tools
## Official tools

```)
