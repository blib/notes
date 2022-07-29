

#### Install all

```

brew install qlcolorcode qlstephen qlmarkdown quicklook-json qlimagesize suspicious-package apparency quicklookase qlvideo betterzip 

brew install starship

brew install zsh-completions zsh-history-substring-search zsh-syntax-highlighting 


```

.zshrc

```

eval "$(starship init zsh)"

 if type brew &>/dev/null; then
    FPATH=$(brew --prefix)/share/zsh-completions:$FPATH

    autoload -Uz compinit
    compinit
  fi

export ZSH_HIGHLIGHT_HIGHLIGHTERS_DIR=/opt/homebrew/share/zsh-syntax-highlighting/highlighters
source /opt/homebrew/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
source /opt/homebrew/share/zsh-history-substring-search/zsh-history-substring-search.zsh

#bindkey '^[[A' history-substring-search-up
#bindkey '^[[B' history-substring-search-down

```


Transmition
https://transmissionbt.com/download/

https://code.visualstudio.com/Download
