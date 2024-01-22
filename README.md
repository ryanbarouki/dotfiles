# Various workflow dot files
## Things to do when setting up:
1. Clone this repo in `~/.config`
2. CHANGE THE USERNAME AND EMAIL IN `.gitconfig`

### Setup symlinks
1. Set up all the symbolic links so that each file knows where to look
```
    chmod +x setup.sh
    ./setup.sh
```
### Manual install
1. Install Kitty terminal
2. Install starship terminal stuff like so:
```
    curl -fsSL https://starship.rs/install.sh | bash
```
3. Copy the Sauce Code Pro Nerd Font to `~/.fonts/`
```
    cp ~/.config/nvim/Sauce Code Pro Nerd Font Complete.ttf ~/.fonts/Sauce Code Pro Nerd Font Complete.ttf
```
You can now use this as your font in your terminal preferences.
