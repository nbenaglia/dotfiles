# dotfiles

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
