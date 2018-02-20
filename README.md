# Setup mac for the 1st time


Git setup 1st time
========
1. Setup git https://help.github.com/articles/connecting-to-github-with-ssh/
1. Git set user/email/default editor - https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup

Node and NVM
======
1. Install latest nodeJS https://nodejs.org/en/download/
1. Install nvm https://github.com/creationix/nvm/blob/master/README.md

Shell update to ohmyz
=====================
1. Install ohmyz http://ohmyz.sh/   
   
   ```$sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"```
1. Install powerline theme https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme
1. Install powerline fonts https://github.com/powerline/fonts
    
    ```$sudo apt-get install fonts-powerline```
1. Install homebrew https://brew.sh/
    
    ```$/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```
1. Install pip, powerline-status http://powerline.readthedocs.io/en/master/installation/osx.html# 
1. Edit ~/.zshrc

    ```
    # Path to your oh-my-zsh installation.
    export ZSH=/Users/pkasi/.oh-my-zsh
    plugins=(git)
    source $ZSH/oh-my-zsh.sh
    ZSH_THEME="agnoster"
    export TERM=xterm-256color
    
 1. Edit ~/.vimrc
    ```" Always show statusline
    set laststatus=2

    " Use 256 colours (Use this setting only if your terminal supports 256 colours)
    set t_Co=256

    if $COLORTERM == 'gnome-terminal'
    set t_Co=256
    endif
    syntax on
    " colorscheme molokai
    set tw=72
    set ruler
