# My KDE Rice

My EndeavourOS desktop setup, backed up for rebuilding or moving to another install.

## System

- Distro: EndeavourOS
- Desktop: KDE Plasma 6
- Font: JetBrainsMono Nerd Font
- Shell: Zsh
- Zsh framework: Oh My Zsh
- Zsh prompt theme: Spaceship
- Zsh plugins: zsh-autosuggestions, zsh-syntax-highlighting, fzf, zoxide

## Plasma layout and settings

The `.config/` folder contains my Plasma and KWin settings, including:

- Top panel and desktop widget layout
- Panel widgets:
  - KDE Control Station
  - BatteryaWatch
  - Window Title Fork
  - Plasmusic Toolbar
  - Plasma GNOME Pager
  - KVitals
  - Digital Clock
  - Panel Colorizer
- Desktop widgets:
  - Mike TimeStats
- Keyboard shortcuts
- KWin settings for Krohnkite and Better Blur DX

Install the widgets, Krohnkite, and Better Blur DX on the new system before restoring these settings. The configuration files save settings and layout; they do not necessarily install the widgets or effects themselves.

## Terminal and TUI tools

Applications I use:

- Zen Browser
- Kitty
- Fastfetch
- fetch-git
- Yazi
- btop
- CAVA
- cmatrix
- whyd

My shell setup uses Zsh, Oh My Zsh, the Spaceship prompt theme, and the plugins listed above. Install those separately before restoring my Zsh configuration.

## Assets

- `assets/Grub Themes/` — GRUB theme files
- `assets/SDDM Themes/` — SDDM theme files
- `assets/Wallpapers/` — wallpaper images

The theme files are backed up here, but they still need to be installed and activated on the new system. Follow the installation instructions for each theme and the new system.

## Restore checklist

1. Install EndeavourOS and KDE Plasma 6.
2. Install JetBrainsMono Nerd Font.
3. Install Zen Browser, Kitty, the TUI tools, Zsh, Oh My Zsh, and the Spaceship prompt.
4. Install the Zsh plugins listed above.
5. Install Krohnkite, Better Blur DX, and the Plasma widgets listed above.
6. Back up any existing configuration files on the new system.
7. Copy this repo's configuration files into their corresponding locations in your home directory.
8. Install and activate the GRUB and SDDM themes using their instructions.
9. Log out and back in, then check the panels, widgets, shortcuts, effects, and terminal setup.

Some settings may need adjustment if the new system has a different Plasma/KWin version, screen arrangement, or set of installed widgets.
