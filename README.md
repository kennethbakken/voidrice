# The Voidrice, my forked dotfiles from (Luke Smith <https://lukesmith.xyz>'s dotfiles)

[this voidrice with my forks of the suckless utilities plus bloated but sexy blur](https://raw.githubusercontent.com/kennethbakken/voidrice/master/Pictures/screenshots/pic-full-210223-2248-02.png)

These are the dotfiles deployed by [LARBS](https://larbs.xyz) and as seen on
[my YouTube channel](https://youtube.com/c/lukesmithxyz).

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:
(these are mine forks not luke's)
- [dwm](https://github.com/kennethbakken/dwm) (window manager)
- [dwmblocks](https://github.com/kennethbakken/dwmblocks) (statusbar)
- [st](https://github.com/kennethbakken/st) (terminal emulator)

I also recommend trying out
[mutt-wizard](https://github.com/lukesmithxyz/mutt-wizard), which additionally
works with this setup. It gives you an easy-to-install terminal-based email
client regardless of your email provider. It is integrated into these dotfiles
as well.

## Install these dotfiles and all dependencies

Use [LARBS](https://larbs.xyz) to autoinstall everything:

```
curl -LO https://raw.githubusercontent.com/kennethbakken/LARBS/master/larbs.sh
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/kennethbakken/LARBS/blob/master/progs.csv).
