# Set Up

update ubuntu vim
( default vim can not support dein.vim)
sudo apt-get install vim


install dein.vim

sample code if `git clone dotfiles.git` @homedir

```
curl https://raw.githubusercontent.com/Shougo/dein.vim/master/bin/installer.sh > installer.sh
sh ./installer.sh ~/dotfiles/vim/vimfiles
```

set up local env

```
ln -s ~/dotfiles/vim/_vimrc ~/.vimrc
ln -s ~/dotfiles/vim ~/.vim

```


