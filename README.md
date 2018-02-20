# setup-guide


Git setup 1st time
========
1. Setup git https://help.github.com/articles/connecting-to-github-with-ssh/
1. Git set user/email/default editor - https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup


Shell update to ohmyz
=====================
1. Install ohmyz http://ohmyz.sh/
1. Install powerline theme https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme
1. Install powerline fonts https://github.com/powerline/fonts

1. Install homebrew https://brew.sh/
1. Install pip, powerline-status http://powerline.readthedocs.io/en/master/installation/osx.html#
    Edit ~/.zshrc
    export TERM=xterm-256color

    if [[ -r ~/library/Python/2.7/lib/python/site-packages/powerline/bindings/zsh/powerline.zsh ]]; then
            source ~/Library/Python/2.7/lib/python/site-packages/powerline/bindings/zsh/powerline.zsh
    fi

    Edit ~/.vimrc
    " Always show statusline
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

    python from powerline.vim import setup as powerline_setup
    python powerline_setup()
    python del powerline_setup
    set rtp+=~/Library/Python/2.7/lib/python/site-packages/powerline/bindings/vim

1. Install latest nodeJS https://nodejs.org/en/download/
1. Install nvm https://github.com/creationix/nvm/blob/master/README.md
