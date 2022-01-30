# How to use stow
Go to .dotfiles
Run stow in simulation mode

> stow -nvt ~ {folder}

Flag `-S` is applied by default and sets the symlinks
Flag `-D` removes the symplinks

To restore `.dotfiles` on a brand new system

> cd ~/.dotfiles && ./macos

To check what stow is going to do

> stow -nvSt ~ *

To unstow dotfiles

> cd ~/.dotfiles && ./macos-uninstall
