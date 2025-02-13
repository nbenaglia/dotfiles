# dotfiles

Inspired by: https://github.com/mathiasbynens/dotfiles/

Files to configure a practical bash environment.

To install, run the following from your terminal: (you may want to backup your
existing `~/.vimrc` first)
```
$ cd
$ git clone https://github.com/nbenaglia/dotfiles.git
```
Create symbolic links from your $HOME:
```
ln -s ~/dotfiles/vimrc .vimrc
ln -s ~/dotfiles/inputrc .inputrc
ln -s ~/dotfiles/tmux.conf .tmux.conf
```
## NVIM

```
ln -s ~/mybash/nvim ~/.config/nvim
```

References:
- https://github.com/NvChad/NvChad
- https://github.com/dreamsofcode-io/neovim-rust
- https://github.com/neovim/neovim
- https://github.com/mfussenegger/nvim-dap

Install NVIM
```
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x nvim.appimage
./nvim.appimage
```

Tutorials
- https://www.youtube.com/watch?v=mh_EJhH49Ms
- https://www.youtube.com/watch?v=Mtgo-nP_r8Y
