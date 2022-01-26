```

export BASH_SILENCE_DEPRECATION_WARNING=1
export VISUAL=vim
export EDITOR="$VISUAL"

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion

#  ----------------------------------
#  GIT ALIASES
#  ----------------------------------

alias gs='git status'          # List which files are staged, unstaged, and untracked
alias ga='git add'             # Stage all changes for the next commit. Add a directory or file.
alias gcm='git commit -m'      # Commit the staged snapshot with a message
alias gp='git push'            # Push the branch
alias gpo='git pull origin'
alias gl='git log'

# branches
alias gb='git branch'
alias gco='git checkout'

#  Hack Reactor
alias gtp='git pull upstream master' # Retrieves Toy Problem

  ```
