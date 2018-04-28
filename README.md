# Contains my dot files for osx and reproducible setup. 

## Steps to follow : 

1. Install [maximum-awesome](https://github.com/square/maximum-awesome)

2. Clone this repo.

3. create symlink to the repo file for all dotfiles. Example :

    ln -s -f path/to/repo/.vimrc.local ~/.vimrc.local 

## Specific commands

* For gitignore_global
    * After symlinking to home directory, run : `git config --global core.excludesfile ~/.gitignore_global`
* `brew bundle dump` is used to get list of all homebrew packages(including casks) 
* better touch tool does not export the snaps as they are specific to displays. As per the [issue](https://github.com/fifafu/BetterTouchTool/issues/757), they are not deleted though on importing. 
* For `userChrome.css` here is the location where the file is located : `/Users/PKhurana/Library/Application Support/Firefox/Profiles/6bge7snc.Nightly/chrome`
    * Example run this from the firefox profile directory : `ln -s ~/code/mydotfiles/userChrome.css userChrome.css` 



