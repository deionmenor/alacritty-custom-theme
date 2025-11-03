# Custom Alacritty Theme

A custom Alacritty terminal configuration featuring the Ayu Mirage color scheme with additional personalized settings.

## Theme Preview

**Color Scheme:** Ayu Mirage
**Font:** JetBrainsMono Nerd Font

### Color Palette

- **Background:** `#1f2430`
- **Foreground:** `#cbccc6`
- **Black:** `#212733` / `#686868` (bright)
- **Red:** `#f08778` / `#f58c7d` (bright)
- **Green:** `#53bf97` / `#58c49c` (bright)
- **Yellow:** `#fdcc60` / `#ffd165` (bright)
- **Blue:** `#60b8d6` / `#65bddb` (bright)
- **Magenta:** `#ec7171` / `#f17676` (bright)
- **Cyan:** `#98e6ca` / `#9debcf` (bright)
- **White:** `#fafafa` / `#ffffff` (bright)

## Installation

1. **Backup your existing config** (if any):
   ```bash
   # Linux/macOS
   cp ~/.config/alacritty/alacritty.toml ~/.config/alacritty/alacritty.toml.backup

   # Windows
   copy %APPDATA%\alacritty\alacritty.toml %APPDATA%\alacritty\alacritty.toml.backup
   ```

2. **Copy this config:**
   ```bash
   # Linux/macOS
   cp alacritty.toml ~/.config/alacritty/alacritty.toml

   # Windows
   copy alacritty.toml %APPDATA%\alacritty\alacritty.toml
   ```

3. **Install JetBrainsMono Nerd Font** (required for this config):
   - Download from [Nerd Fonts](https://www.nerdfonts.com/font-downloads)
   - Or install via package manager (e.g., `brew install --cask font-jetbrains-mono-nerd-font`)

## Features

- **Ayu Mirage color scheme** - A dark, elegant theme with excellent contrast
- **JetBrainsMono Nerd Font** - Beautiful monospace font with programming ligatures
- **Blinking block cursor** - Customizable cursor style
- **10,000 line scrollback** - Extended history buffer
- **WSL integration** - Pre-configured for Windows Subsystem for Linux
- **Useful keybindings** - Standard shortcuts for copy/paste, font sizing, search, and more

## Customization

Feel free to modify the configuration to suit your preferences:

- **Font size:** Adjust `size` in the `[font]` section (line 35)
- **Opacity:** Change `opacity` in the `[window]` section (line 11)
- **Colors:** Modify any color values in the `[colors]` section (lines 66-101)
- **Shell:** Update `[terminal.shell]` section to use your preferred shell (lines 57-65)

## License

Feel free to use and modify as you wish.
