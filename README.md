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

# Neovim
mkdir -p ~/.config/nvim/
ln -s ~/mybash/init.vim ~/.config/nvim/init.vim
```
