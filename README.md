# my-bash

Files to configure a practical bash environment.

To install, run the following from your terminal: (you may want to backup your
existing `~/.vimrc` first)
```
$ cd
$ git clone https://github.com/nicoben/my-bash.git
```
Create symbolic links from your $HOME:
```
ln -s ~/my-bash/vimrc .vimrc
ln -s ~/my-bash/inputrc .inputrc
ln -s ~/my-bash/tmux.conf .tmux.conf
```
## NVIM

```
ln -s ~/mybash/nvim ~/.config/nvim
```

Source: https://www.youtube.com/watch?v=mh_EJhH49Ms

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

