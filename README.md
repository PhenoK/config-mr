# $HOME configs
1. .zshrc
2. .vimrc
3. .tmux.conf
4. .gitconfig
    - user, email, editor
    - credential.helper
5. .jupyter/jupyter_notebook_config.py
    - password
6. config.sh
    - for building zplug, tmux (tpm), vim plugins

## Usage for dummies
```bash
rm -Rvf ~/.config ~/.mrconfig ~/config.sh ~/.jupyter/jupyter_notebook_config.py ~/.gitignore.d/ ~/.gitconfig ~/.zshrc ~/.vimrc ~/.ycm_extra_conf.py ~/.tmux.conf ~/README.md
cd; vcsh clone https://github.com/Shen-Jing/config-mr.git
mr update; exec $SHELL
```