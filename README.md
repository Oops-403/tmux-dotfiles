# tmux-dotfiles
tmux config files

## Another Better Choose

[gpakosz repo link](https://github.com/gpakosz/.tmux.git)

- get the config
```shell
git clone https://github.com/gpakosz/.tmux.git /path/to/oh-my-tmux
```

- soft link the main config 
```shell
ln -s -f /path/to/oh-my-tmux/.tmux.conf ~/.tmux.conf
```

- soft link the local config
```shell
cp /path/to/oh-my-tmux/.tmux.conf.local ~/.tmux.conf.local
```
