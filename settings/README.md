# MySettings
A simple private repo where I can store my configuration files, feel free to fork and use these idc. I will not customize these for you. This is public only so I can use the one liners below.

## The Font That I Typically Use is `RobotoMono Nerd Font`
[Download RobotoMono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/latest/download/RobotoMono.zip)

## The ZSH Theme I Use Is Powerlevel10k
[Powerlevel10k Repository](https://github.com/romkatv/powerlevel10k)

## Windows Terminal
Place the icons anywhere and then add the `icon` field to a profile. Here is an example:
```json
{
    "icon": "D:\\Pictures\\WindowsTerminal\\{icon-name}.png"
}
```

### Adding A Context Menu
If you would like the option to right click and open a new "Windows Terminal here" visit this repositoy:
https://github.com/lextm/windowsterminal-shell

## ZSH Plugins
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md)
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md)

## One Line Updaters
Here are some oneliners to run if you want to set your profile.
### Ubuntu
```bash
wget -O ~/.zshrc https://raw.githubusercontent.com/Banakin/Banakin/master/settings/zsh/ubuntu.zshrc && source ~/.zshrc
```

### macOS
```bash
wget -O ~/.zshrc https://raw.githubusercontent.com/Banakin/Banakin/master/settings/zsh/macos.zshrc && source ~/.zshrc
```

### Vim
```bash
wget -O ~/.vimrc https://raw.githubusercontent.com/Banakin/Banakin/master/settings/vim/vimrc
```
