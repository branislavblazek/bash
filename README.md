Clone this repo
`git init clone`

to access functions even outside DIR
```
cd ~
vim .zshrc
```
then paste to end of file:
```
// GIT_REPO_DIR = where is this project located
GIT_REPO_DIR=/Users/branislav/Documents/Code/Personal/bash/

. ${GIT_REPO_DIR}alias
. ${GIT_REPO_DIR}calc
. ${GIT_REPO_DIR}seeds
. ${GIT_REPO_DIR}git_fn
. ${GIT_REPO_DIR}frizip
```
