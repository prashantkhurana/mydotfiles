# Contains my dot files for osx and reproducible setup. 

## Steps to follow : 

1. Install [maximum-awesome](https://github.com/square/maximum-awesome)

2. Clone this repo.

3. create symlink to the repo file for all dotfiles. Example :

    ln -s -f path/to/repo/.vimrc.local ~/.vimrc.local 

## Specific commands

 * For gitignore_global
    * After symlinking to home directory, run : `git config --global core.excludesfile ~/.gitignore_global`

