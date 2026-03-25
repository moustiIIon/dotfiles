# dotfiles

Arch rice config

## Setup

| Component       | Tool                        |
|-----------------|-----------------------------|
| WM              | Hyprland                    |
| Bar             | Waybar                      |
| Terminal        | Kitty + Foot                |
| Shell           | Zsh (Powerlevel10k)         |
| Editor          | Neovim (LazyVim)            |
| Launcher        | Rofi + Fuzzel               |
| Notifications   | SwayNC                      |
| File manager    | Thunar                      |
| Logout menu     | Wlogout                     |
| Screenshot      | Grim + Slurp + Swappy       |
| Wallpaper       | Swww                        |
| Music           | Spicetify + MPD + rmpc      |
| Visualizer      | Cava                        |
| Fetch           | Fastfetch                   |
| Theme engine    | Matugen                     |
| Font            | JetBrainsMono NF            |
| GTK Theme       | Material You (matugen)      |

## Structure

```
~
├── .zshrc
├── .p10k.zsh
└── .config/
    ├── hypr/          # Hyprland, hypridle, hyprlock
    ├── waybar/        # Bar with multiple themes (default, minimal, xtend)
    ├── kitty/         # Terminal emulator
    ├── nvim/          # Neovim config (LazyVim)
    ├── rofi/          # App launcher + scripts
    ├── fuzzel/        # Wayland-native launcher
    ├── swaync/        # Notification center
    ├── wlogout/       # Session menu
    ├── btop/          # System monitor
    ├── fastfetch/     # System info
    ├── cava/          # Audio visualizer
    ├── tmux/          # Terminal multiplexer
    ├── mpv/           # Video player
    ├── spicetify/     # Spotify theming
    ├── swappy/        # Screenshot annotation
    ├── satty/         # Image annotation
    ├── starship.toml  # Shell prompt (alt)
    ├── gtk-3.0/
    ├── gtk-4.0/
    ├── qt5ct/
    └── qt6ct/
```


### Dependencies (Arch)

```bash
sudo pacman -S hyprland waybar kitty foot rofi fuzzel swaync wlogout \
               btop fastfetch cava tmux mpv swappy grim slurp swww \
               neovim zsh starship matugen
yay -S spicetify-cli
```
