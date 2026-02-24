# Dotfiles

Personal Linux dotfiles repository.

This repo contains configuration files for my desktop environment, terminal, shell, editors, and related tools (Hyprland, Waybar, Kitty, Neovim, Zsh, etc.).

It is **not** intended to store application runtime data (browsers, Electron apps, game saves).

## Dependencies

All required packages are listed in:

- `pacman-packages.txt` → official repository packages  
- `yay-packages.txt` → AUR packages  

Use them to replicate the environment:

```bash
sudo pacman -S --needed - < pacman-packages.txt
yay -S --needed - < yay-packages.txt
```

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/392ffaa2-fa72-4854-9c1f-38e3b4bf9b12" />
