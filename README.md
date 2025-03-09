# My dev environment

### Shell
* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
* [z](https://github.com/rupa/z/)


### Git

```
# Add these to your ~/.gitconfig file under the [alias] section

# Basic shortcuts
st = status
co = checkout
ci = commit
br = branch
lg = log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit

# View commits as a graph with branches
graph = log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(auto)%d%C(reset)'

# Amend the previous commit without changing the commit message
amend = commit --amend --no-edit

# Show changes from the last commit
last = log -1 HEAD --stat

# Unstage a file
unstage = reset HEAD --

# Undo the last commit but keep changes
undo = reset HEAD~1 --soft

# See all changes since your last commit
changes = diff

# See which files have changes
changed = diff --name-only

# Add all changes including untracked files
ada = add --all

# Show a pretty formatted log with limited entries
slog = log --oneline --decorate --graph -20

# List all aliases
aliases = config --get-regexp ^alias\\.
```
