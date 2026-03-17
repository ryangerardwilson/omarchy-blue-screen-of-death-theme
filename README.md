# blue_screen_of_death

An Omarchy extra theme inspired by the Windows Blue Screen of Death, but rewritten as a thank-you note for finally pushing us to Linux.

This repository follows Omarchy's extra-theme layout:

- Theme files live at the repository root.
- Wallpapers live in `backgrounds/`.
- The repo name uses the `omarchy-<theme>-theme` pattern so `omarchy-theme-install` resolves the theme name correctly.

## Install

```bash
omarchy-theme-install https://github.com/ryangerardwilson/omarchy-blue_screen_of_death-theme.git
```

If you clone it manually:

```bash
git clone https://github.com/ryangerardwilson/omarchy-blue_screen_of_death-theme.git ~/.config/omarchy/themes/blue_screen_of_death
omarchy-theme-set blue_screen_of_death
```

## Included Overrides

- `colors.toml` for Omarchy-generated theme files
- `alacritty.toml` to keep terminal text white on the BSOD blue background
- `hyprland.conf` for white active borders and light-gray inactive borders
- `neovim.lua`, `vscode.json`, and `icons.theme` for app-specific alignment
- `wallpaper.svg`, `preview.png`, and `backgrounds/0-blue-screen-of-death.png`

## Preview

![blue_screen_of_death preview](preview.png)
