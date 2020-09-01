# OhMyGit! 
Git Guide for Beginners

## Git Config
You have to config your git for the first time

We will configure
* Name
* Email
* Default Editor
* DiffTool
* MergeTool

### Steps:
1. open your terminal/ git bash (for windows)
1. run the following lines

```bash
$ git config --global user.name "Hagar Usama"

$ git config --global user.name "YOUR EMAIL"

$ git config --global core.editor "YOUR EDITOR"

$ git config --global diff.tool "YOUR DIFFTOOL"

$ git config --global diff.merge "YOUR MERGETOOL"

$ git config --global difftool.prompt false


 ```


### Hints:
1. Use 'code' as your editor, personally I use nano
1. Use diffmerge or meld as your difftool and diffmerge
    > do not forget to install them before configuring
1. check your configuration with  `git config --list`




## Basic Git commands [1]
1. `git init` : initialize a new git repo
1. `git clone`: create a local copy of a project tht already remotely exists
1. `git add`: stages a change, takes a snapshot
1. `git commit`: save the snapshot to the project history
1. `git push`: updates the remote repo with any commits made locally
1. `git pull`: updates the local line of development with updates from its remote repo
1. `git status`: show the status of changes as untracked, modified, or staged
1. `git branch`: shows the branches being worked on locally
1. `git merge`: merges lines of development together.
1. `git checkout`: switches branches or creates a new branch

[1]: https://guides.github.com/introduction/git-handbook/


## What else

### Markdown: see MD.md