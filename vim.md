# Vim

## Install Vim

```
brew install vim
```

## Install vim-plug

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

## Add config

Copy `https://raw.githubusercontent.com/askalot/dotfiles/master/vimrc` to `~/.vimrc`.

## Install plugins

```
vim +'PlugInstall --sync' +qa
```

Reference: https://github.com/junegunn/vim-plug/issues/675

