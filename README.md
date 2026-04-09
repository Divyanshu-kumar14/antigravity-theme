<div align="center">
  <h1>🌌 Antigravity Theme</h1>
  <p>A sleek, modern, and high-contrast <b>Gruvbox Dark Hard</b> aesthetic theme explicitly optimized for <b>Omarchy Linux</b> and <b>Hyprland</b>.</p>

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Platform](https://img.shields.io/badge/Platform-Linux%20%2F%20Wayland-blue.svg)]()
  [![WM](https://img.shields.io/badge/Window%20Manager-Hyprland-blueviolet.svg)]()
  [![Theme](https://img.shields.io/badge/Theme-Gruvbox%20Dark-orange.svg)]()
  [![RAM](https://img.shields.io/badge/Optimized%20For-Low%20RAM-red.svg)]()
</div>

<br>

<p align="center">
  <b>Antigravity</b> provides a cohesive, eye-friendly, and consistent experience across your entire Linux environment—bridging the legendary Gruvbox color palette with modern Wayland and Hyprland aesthetics.
</p>

---

## 📑 Table of Contents
- [✨ Features](#-features)
- [🎨 Color Palette](#-color-palette)
- [📸 Screenshots](#-screenshots)
- [📦 Supported Applications](#-supported-applications)
- [📂 Repository Structure](#-repository-structure)
- [🚀 Installation](#-installation)
  - [Omarchy native installation](#omarchy-native-installation)
  - [Manual Component Installation](#manual-component-installation)
- [💡 Troubleshooting](#-troubleshooting)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

---

## ✨ Features

- **High-Contrast "Gruvbox Dark Hard" Aesthetic:** Completely styled uniformly from terminal emulators to the system monitor.
- **Low RAM Optimization:** The `hyprland.conf` is strictly optimized to minimize compositor overhead, disabling unnecessary blur and heavy shadows for maximal performance.
- **Lean & Smooth Animations:** Custom Bezier curves explicitly tuned to provide buttery macOS-like fade and slide transitions without massive GPU/RAM spikes.
- **Universal GTK Styling:** Deep integration into `gtk.css` ensures apps respect the global layout and color tokens.
- **Comprehensive Terminal Support:** Plug-and-play configs for Kitty, Alacritty, and Ghostty.

## 🎨 Color Palette

The theme strictly adheres to the core Gruvbox color tokens for maximum eye comfort, utilizing high-contrast backgrounds to make neon edges pop.

| Color | Hex Check | Role | Hex Code |
|-------|-----------|------|----------|
| **Background** | <img src="https://via.placeholder.com/15/1d2021/000000?text=+" width="15" height="15"> | Main Base UI | `#1d2021` |
| **Foreground** | <img src="https://via.placeholder.com/15/ebdbb2/000000?text=+" width="15" height="15"> | Text / Active Borders | `#ebdbb2` / `#fbf1c7` |
| **Primary Accent** | <img src="https://via.placeholder.com/15/cc241d/000000?text=+" width="15" height="15"> | Error / Critical | `#cc241d` |
| **Secondary Accent**| <img src="https://via.placeholder.com/15/b8bb26/000000?text=+" width="15" height="15"> | Success / Notification | `#b8bb26` |
| **Tertiary Accent**| <img src="https://via.placeholder.com/15/fabd2f/000000?text=+" width="15" height="15"> | Warnings / UI Elements | `#fabd2f` |
| **Selection BG** | <img src="https://via.placeholder.com/15/a89984/000000?text=+" width="15" height="15"> | Highlight text / borders | `#a89984` |

*See `colors.toml` for the full terminal ANSI mappings.*

## 📸 Screenshots

<p align="center">
  <img src="screenshots/01-fastfetch.png" alt="Fastfetch Overview" width="800">
  <br><i>Fastfetch showcasing the Antigravity theme details and Gruvbox palette in the terminal.</i>
</p>

<p align="center">
  <img src="screenshots/02-monitoring.png" alt="System Monitoring" width="800">
  <br><i>System resource monitoring alongside OBS Studio under Hyprland.</i>
</p>

<p align="center">
  <img src="screenshots/03-desktop.png" alt="Clean Desktop" width="800">
  <br><i>Clean workspace displaying the high-quality desktop wallpaper and an active Mako notification.</i>
</p>

## 📦 Supported Applications

Antigravity themes the modern Linux stack from the ground up:

### Desktop & Wayland Shell
- **[Hyprland](https://hyprland.org/):** Core window manager rules (`hyprland.conf`), monitors (`monitors.conf`), and picker styling (`hyprland-preview-share-picker.css`)
- **[Hyprlock](https://github.com/hyprwm/hyprlock):** Screen locker integration (`hyprlock.conf`)
- **[Waybar](https://github.com/Alexays/Waybar):** Status bar (`waybar.css`)
- **[Mako](https://github.com/emersion/mako):** Notification daemon (`mako.ini`)
- **[SwayOSD](https://github.com/ErikReider/SwayOSD):** On-screen volume/brightness popups (`swayosd.css`)

### App Launchers
- **[Walker](https://github.com/abenz1267/walker):** Premium app runner with custom layout (`walker.css`, `walker-layout.xml`)
- **[Wofi](https://hg.sr.ht/~scoopta/wofi):** Minimalist fallback application palette (`wofi.css`)

### Terminal Emulators
- **[Alacritty](https://alacritty.org/)** (`alacritty.toml`)
- **[Kitty](https://sw.kovidgoyal.net/kitty/)** (`kitty.conf`)
- **[Ghostty](https://ghostty.org/)** (`ghostty.conf`)

### Developer Tools & Editors
- **GTK:** Global GTK layout (`gtk.css`)
- **[Neovim](https://neovim.io/):** Colorscheme bridge (`neovim.lua`)
- **VSCode:** Raw palette values (`vscode.json`)
- **[Obsidian](https://obsidian.md/):** Note editor themes (`obsidian.css`)
- **[Superfile](https://github.com/mhucka/superfile):** CLI File Manager (`antigravity.toml`)
- **[btop](https://github.com/aristocratos/btop):** Terminal task manager (`btop.theme`)

### Communication & Entertainment
- **[Firefox](https://www.mozilla.org/firefox/):** Custom `userChrome.css` hiding the tab bar and recoloring the entire browser chrome (`firefox-userChrome.css`)
- **[Discord](https://github.com/Vencord/Vesktop) (Vesktop / Vencord):** Full Gruvbox reskin for channels, chat, embeds, and modals (`discord-vencord.css`)
- **[Spotify](https://spicetify.app/) (Spicetify):** Complete theme with `color.ini` and `user.css` for Spicetify (`spicetify-color.ini`, `spicetify-user.css`)
- **[Telegram Desktop](https://desktop.telegram.org/):** Native `.tdesktop-theme` covering chat, sidebar, media viewer, and calls (`telegram.tdesktop-theme`)

## 📂 Repository Structure

```text
antigravity-theme/
├── backgrounds/                      # Optimized JPEG wallpapers (bg-1, bg-2, bg-3)
├── screenshots/                      # Theme showcase screenshots
├── alacritty.toml                    # Alacritty terminal config
├── antigravity.toml                  # Superfile file manager color schema
├── btop.theme                        # btop system monitor styling
├── chromium.theme                    # Chromium GTK theme name
├── colors.toml                       # Global ANSI color hex mappings
├── discord-vencord.css               # Discord Vencord/Vesktop theme
├── firefox-userChrome.css            # Firefox UI chrome styling
├── ghostty.conf                      # Ghostty terminal config
├── gtk.css                           # Custom GTK application styling
├── hyprland.conf                     # Hyprland WM config (low-RAM optimized)
├── hyprland-preview-share-picker.css # Screen share picker styling
├── hyprlock.conf                     # Screen locker config
├── icons.theme                       # Icon theme name
├── keyboard.rgb                      # Keyboard backlight color (#ebdbb2)
├── kitty.conf                        # Kitty terminal config
├── mako.ini                          # Notification daemon styling
├── monitors.conf                     # Monitor resolution & scaling
├── neovim.lua                        # Neovim colorscheme bridge
├── obsidian.css                      # Obsidian note editor theme
├── spicetify-color.ini               # Spicetify Spotify color tokens
├── spicetify-user.css                # Spicetify Spotify element styling
├── telegram.tdesktop-theme           # Telegram Desktop theme
├── vscode.json                       # VS Code raw palette values
├── walker.css                        # Walker app runner theme
├── walker-layout.xml                 # Walker custom GTK layout
├── waybar.css                        # Waybar status bar theme
└── wofi.css                          # Wofi app drawer theme
```

## 🚀 Installation

### Omarchy Native Installation
The quickest way to install is via Omarchy's native RICE installer:

```bash
# Clone the repository to an accessible location
git clone https://github.com/Divyanshu-kumar14/antigravity-theme.git

# Install using the local path
omarchy-theme-install ./antigravity-theme
```

Or deploy directly from the repository link:
```bash
omarchy-theme-install https://github.com/Divyanshu-kumar14/antigravity-theme.git
```

### Manual Component Installation
To manually copy files into your setup for tools without the Omarchy installer, here are quick references:
- **Superfile:** Copy `antigravity.toml` to `~/.config/superfile/theme/` and update your `config.toml`.
- **BTOP:** Copy `btop.theme` to `~/.config/btop/themes/antigravity.theme`.
- **Mako:** Copy `mako.ini` to `~/.config/mako/config`.

#### Communication & Entertainment
- **Firefox:**
  ```bash
  # Enable custom stylesheets in about:config
  # Set: toolkit.legacyUserProfileCustomizations.stylesheets = true
  # Then find your profile folder via about:support → "Profile Folder"
  mkdir -p "$(find ~/.mozilla/firefox -name '*.default-release' -type d)/chrome"
  cp firefox-userChrome.css "$(find ~/.mozilla/firefox -name '*.default-release' -type d)/chrome/userChrome.css"
  # Restart Firefox
  ```
- **Discord (Vesktop / Vencord):**
  ```bash
  # In Vesktop/Vencord: Settings → Vencord → Themes → paste or load file
  cp discord-vencord.css ~/.config/vesktop/themes/antigravity.css
  ```
- **Spotify (Spicetify):**
  ```bash
  mkdir -p ~/.config/spicetify/Themes/Antigravity
  cp spicetify-color.ini ~/.config/spicetify/Themes/Antigravity/color.ini
  cp spicetify-user.css ~/.config/spicetify/Themes/Antigravity/user.css
  spicetify config current_theme Antigravity color_scheme base
  spicetify apply
  ```
- **Telegram Desktop:** Settings → Chat Settings → Choose from file → select `telegram.tdesktop-theme`.

## 💡 Troubleshooting

- **Flickering Notifications:** If Mako notifications flicker or cause dimming, ensure that `layer-shell` blur is disabled or managed correctly in your `hyprland.conf`. (The current `hyprland.conf` disables blur globally to mitigate this).
- **RAM Spikes during Animations:** Antigravity provides leaner bezier curves. If you experience lag, confirm that you are using the `animation = windowsIn, ...` values listed in this repo and that shadows are disabled.

## 🤝 Contributing

Contributions are always welcome. To contribute:
1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'feat: Add AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

Ensure any new CSS or config files follow the uniform Gruvbox Dark Hard values established in `colors.toml`.

## 📜 License

Distributed under the **MIT License**. See [LICENSE](LICENSE) for more information.
