# 🛠️ My Dotfiles (Arch Linux)

A collection of configuration files for my **Arch Linux** setup. This repo helps me quickly set up and sync my development environment across machines.

## 🐧 System

- OS: Arch Linux (Wayland-based setup)
- WM/DE: Hyprland + KDE components
- Shell: Zsh / Bash (custom prompt via Starship)
- Terminal: Kitty

## 📁 Includes Configs For:

- Neovim (`nvim/`)
- Hyprland (`hypr/`)
- Waybar, Rofi, Dunst, Wlogout
- Terminal tools: Kitty, Starship, Fastfetch, Lazygit
- KDE & GTK themes: Kvantum, qt5ct, qt6ct, GTK 3/4
- Code editors: VS Code (`Code - OSS/`), JetBrains
- Tools: Zathura, Htop, Go, PulseAudio
- Systemd user services
- And more...

## 🚫 Excluded

Some user-specific or auto-generated files are excluded via `.gitignore`, like:

- `dconf/`, `pulse/`, `session/`
- `mimeapps.list`, `user-dirs.*`
- Any private or sensitive data

## 📦 Usage

To set up these dotfiles using the **bare Git repo method** (recommended):

```bash
git clone --bare https://github.com/depuc/dotfiles.git $HOME/.dotfiles
