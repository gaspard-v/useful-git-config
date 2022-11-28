# useful-git-config

List of useful config for Git

## List git settings

`git config -l`

## Set a global gitignore

`git config --global core.excludesfile /path/to/.gitignore`

## Store credential in cache

Warning ! this config save your password in **plaintext**
`git config --global credential.helper store`
