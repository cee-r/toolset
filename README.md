# toolset

## Terminal

Preferences
```shell
export PS1="%{%F{165}%}%n%{%F{171}%}@%{%F{213}%}%m %{%F{219}%}%1~ %{%f%}$ "
export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
```

- ZSH prompt generator https://robotmoon.com/zsh-prompt-generator/

```shell

# Aliases

# Utilities
alias clr="clear" # Clear terminal screen
alias ll="ls -al" # List all files in curr dir in long list
alias ldir="ls -al | grep ^d" # List all dirs in curr dir in long list
alias o="open ." # Open curr dir in finder

# Location shortcuts
alias <alias>='cd <path/>'

# Set git user
alias <alias>='git config user.email "<email>"; git config user.name "<username>"'

# Add agent
alias <alias>='eval "$(ssh-agent -s)"; ssh-add <path_to_key>'
```

Tools
```shell
# Vim
# .vimrc
set tabstop=2 softtabstop=2 shiftwidth=2
set expandtab
set number ruler
set autoindent smartindent
syntax enable

# WSL / Linux

desktop-file-utils
```

## Mac
- homebrew
- xcode
- simulator
  
## Windows
- WSL
- omyzsh

## Linux

## ENV & Managers
- PHP / composer
- Node / npm
- Pythong / pip

## Misc
- git
- sass

## Applications
- phpstorm
- vscode
- docker

## Themes
- dracula
