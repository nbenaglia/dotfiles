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
ln -s ~/dotfiles/config/.vimrc .vimrc
ln -s ~/dotfiles/config/.inputrc .inputrc
ln -s ~/dotfiles/config/.tmux.conf .tmux.conf
```
