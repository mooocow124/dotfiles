# Dotfiles

Hey, here are my dotfiles! I'll put them all here.
I use Bash now, the zshrc is leftover in case I forgot to migrate something.

To get set up with my dotfiles, get stow first of all.

On Debian and it's derivatives: `sudo apt update && sudo apt install stow`

I dunno for other distros.
Then clone this repo and go into the directory where you've cloned it.
And execute these commands:
```
stow shell fastfetch kitty nvim # To apply dotfiles
curl -L https://raw.github.com/git/git/master/contrib/completion/git-prompt.sh > ~/.bash_git # For Git integration into Bash prompt
```

## Other theming

I use Catppuccin Frappe GTK, Kitty, Chromium, and Kvantum theme, and Pop OS with all COSMIC stuff disabled and using my own extensions.

### GNOME Extensions
* Dash to Dock
* Pano Clipboard Manager
* Improved Workspace Indicator
* GSConnect
* Fly-Pie
* User Themes (ofc)
* Emoji Selector
* Caffeine
* Blur My Shell
* Pop Shell
* Ubuntu AppIndicators

To get Pop Shell on non-Pop distros, you might have to compile yourself, IDK.

### GNOME Extension Configs

**Dash to Dock**: Act like panel, icon size 32, transparency 50%
Rest extensions are vanilla.
