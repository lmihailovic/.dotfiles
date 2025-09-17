# dotfiles

These dotfiles are just some configurations I deem worth keeping around.
No fiddling with `stow(1)` because that's too much overhead for something you do once in a blue moon. Just copy and paste files as needed.

## Files
- acme\_alacitty.toml - custom acme inspired color scheme theme for alacritty
- acme\_zutty - acme inspired configs for [zutty](https://tomscii.sig7.se/zutty/) terminal. Requires `Go Mono` installed on the system. Add to the end of `~/.Xresources`, and then run `xrdb -merge ~/.Xresources` for changes to apply
