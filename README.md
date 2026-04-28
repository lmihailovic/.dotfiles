# dotfiles

These dotfiles are just some configurations I deem worth keeping around.
No fiddling with `stow(1)` because that's too much overhead for something you do once in a blue moon. Just copy and paste files as needed.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/62304afe-c53e-43eb-bc0c-62573c1555ce" />

## Files

| File | Description | Location |
|------|-------------|----------|
| `acme_alacritty.toml` | my custom acme inspired color scheme theme for `alacritty` | `.config/alacritty` |
| `acme_zutty` | my custom acme inspired config for [zutty](https://tomscii.sig7.se/zutty/) | Add to the end of `~/.Xresources`, and then run `xrdb -merge ~/.Xresources` for changes to apply. Requires the [Go font](https://aur.archlinux.org/packages/ttf-go). |
| `acme.theme` | my custom acme inspired color scheme for `xfce4-terminal` | `~/.local/share/xfce4/terminal/colorschemes` |
| `mpv.conf` | duh. | `~/.config/mpv/mpv.conf` |
| `fish/` | technically a directory, but such is `fish` | `~/.config/fish/` |

## Miscellaneous

Resources used, but not suited to be stored in this repository:
1. [Go font](https://aur.archlinux.org/packages/ttf-go)
2. [Redmond97 SE](https://codeberg.org/Sliver_X/Redmond97-SE) (Mystery theme)
3. [Bluecurve icons](https://github.com/neeeeow/Bluecurve)
