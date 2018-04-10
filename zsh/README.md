# MY DOTFILES
========
My zsh configuration.
---

## Screenshot

![Screenshot of my Python setup](https://github.com/iSushil/.dotfiles/blob/master/assets/zsh.png)

## Installation

**Warning:** If you want to give these dotfiles a try, you should first fork this repository, review the code, and remove things you don’t want or need. Don’t blindly use my settings unless you know what that entails. **Use at your own risk!**

### Software Installations
- Installing [ZSH](https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH)

### Setup Using Git

You can clone the repository wherever you want. (I like to keep it in `~/.dotfiles`)

To install, `cd` into your local `.dotfiles/` repository and Run `source ./install.sh` or the script below. It will create necessary symlinks into your required locations with stow.

```bash
stow zsh
```

## Feedback

Suggestions/improvements are [welcome](https://github.com/iSushil/.dotfiles/issues)!
