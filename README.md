# OH MY CYGWIN

Fork from [haithembelhaj/oh-my-cygwin](https://github.com/haithembelhaj/oh-my-cygwin)

This sets up a working ZSH Shell on cygwin, powered by [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) and the [apt-cyg](https://github.com/transcode-open/apt-cyg) package manager.

# Setup

Install [cygwin](http://www.cygwin.com/) with wget (check wget in the installation process) then start cygwin and execute 

    wget --no-check-certificate https://raw.github.com/fengyc/oh-my-cygwin/master/oh-my-cygwin.sh -O - | sh

Change zsh theme and load plugins

    vi ~/.zshrc
    # ZSH_THEME = "random"
    # plugins=(git git-flow svn)
    
Themes and plugins can be found in ~/.oh-my-zsh
    
Enjoy!
