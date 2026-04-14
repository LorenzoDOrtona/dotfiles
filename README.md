# Dotfiles

Personal configuration files for a Wayland-based Hyprland environment.

## 🛠 Core Components
- **WM:** [Hyprland](https://hyprland.org/)
- **Terminal:** [Kitty](https://sw.kovidgoyal.net/kitty/)
- **Shell:** [Zsh](https://www.zsh.org/)
- **Editor:** [Neovim](https://neovim.io/) (LazyVim)
- **Bar:** [Waybar](https://github.com/Alexays/Waybar)
- **Idle/Lock:** Hypridle & Hyprlock

## 🚀 Setup
This repo is organized for [GNU Stow](https://www.gnu.org/software/stow/).

1. **Clone the repo:**
   ```bash
   git clone git@github.com:LorenzoDOrtona/dotfiles.git ~/dotfiles
   cd ~/dotfiles
   ```

2. **Deploy configurations:**
   Use `stow` to symlink configs to your home directory:
   ```bash
   stow bin hypr kitty nvim waybar zsh
   ```

## 📂 Structure
- `bin/`: Local scripts
- `hypr/`: Hyprland, Idle, and Lock configs
- `kitty/`: Terminal emulator settings & themes
- `nvim/`: LazyVim setup
- `waybar/`: Status bar styling
- `zsh/`: Shell configuration
