<div align="center">
  <h1>🌌 Antigravity Theme</h1>
  <p>A sleek, modern, and high-contrast <b>Gruvbox Dark Hard</b> aesthetic theme for Omarchy Linux and Hyprland.</p>
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Platform](https://img.shields.io/badge/Platform-Linux%20%2F%20Wayland-blue.svg)]()
  [![WM](https://img.shields.io/badge/Window%20Manager-Hyprland-blueviolet.svg)]()
</div>

<br>

## 🎨 Overview

**Antigravity** has evolved into a highly refined theme that bridges the legendary **Gruvbox Dark Hard** palette (`#1d2021`, `#cc241d`, `#b8bb26`, etc.) with modern Wayland/Hyprland aesthetics. It provides a cohesive, eye-friendly, and consistent experience across your entire Linux environment—from your terminal to your GTK applications and application launchers.

## 📸 Screenshots

*(Screenshots coming soon...)*

## ✨ Supported Applications & Components

The Antigravity theme provides out-of-the-box styling and configurations for a wide variety of tools to ensure a completely uniform desktop experience:

### Desktop Environment
- **[Hyprland](https://hyprland.org/):** Core window manager configuration (`hyprland.conf`, `monitors.conf`) incorporating smooth animations and Gruvbox borders.
- **Hyprlock:** Custom screen locker configuration (`hyprlock.conf`).
- **Waybar:** Status bar styling (`waybar.css`).
- **Mako:** Minimalist notification daemon (`mako.ini`).
- **SwayOSD:** Custom on-screen displays (`swayosd.css`).

### Application Launchers
- **[Wofi](https://hg.sr.ht/~scoopta/wofi):** Themed application palette (`wofi.css`).
- **[Walker](https://github.com/abenz1267/walker):** Premium, fast app runner styling (`walker.css`).

### Terminals
- **[Alacritty](https://alacritty.org/)** (`alacritty.toml`)
- **[Kitty](https://sw.kovidgoyal.net/kitty/)** (`kitty.conf`)
- **[Ghostty](https://ghostty.org/)** (`ghostty.conf`)

### Editors & Utilities
- **GTK:** Complete GTK theme configuration (`gtk.css`) matching the UI.
- **[Neovim](https://neovim.io/):** Initial setup integrating the color palette (`neovim.lua`).
- **VSCode:** Color palette (`vscode.json`).
- **[btop](https://github.com/aristocratos/btop):** System monitor theme (`btop.theme`).
- **[Superfile](https://github.com/mhucka/superfile):** File manager theme (`antigravity.toml`).
- **Browser:** Chromium theming integration (`chromium.theme`).

## 🖼️ Backgrounds

Included in the `/backgrounds` directory are custom high-quality wallpapers (`bg-1.jpg`, `bg-2.jpg`, `bg-3.jpg`) curated to sync perfectly with the Gruvbox-inspired aesthetic. 

## 🚀 Installation

### Using Omarchy Theme Installer

To install this theme natively on Omarchy Linux, use the `omarchy-theme-install` command and point it to the repository OR use your local path:

```bash
# Clone the repository
git clone https://github.com/Divyanshu-kumar14/antigravity-theme.git

# Install locally
omarchy-theme-install ./antigravity-theme
```

Or install directly from the repository URL:
```bash
omarchy-theme-install https://github.com/Divyanshu-kumar14/antigravity-theme.git
```

### Manual Component Installation (Example: Superfile)
- This theme includes a Superfile theme configuration. 
- Copy `antigravity.toml` to `~/.config/superfile/theme/` and edit your `config.toml` to set `theme = 'antigravity'`.

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
