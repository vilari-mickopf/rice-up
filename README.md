# rice-up

Autoconfiguring based on my [dotfiles](https://github.com/vilari-mickopf/dotfiles). \
**Use at your own risk!**

## Usage
```bash
./rice --wm --vim --sh --boot
```

Options:
- `--wm`: i3gaps with i3block, i3lock, st, ranger, dmenu, rofi, ly, oblogout,...
- `--vim`: <3
- `--sh`: zsh
- `--boot`: refind

- `--all`: `--wm --sh --vim --boot`
- noargs = `--all`

Script will autoinstall needed packages using pacman. If you are not on arch, `--config-only` argument will skip installation part.

```bash
./rice --vim --sh --config-only
```
