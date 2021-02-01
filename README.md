# OhMyGit! 
Git Guide for Beginners
---

## Todo
* [ ] what is git?
* [ ] why git?
* [ ] what is github?
* [ ] why github?
* [ ] Start with an exisiting repo
    - [*] clone
    - [*] branch
    - [ ] add
    - [ ] commit
    - [ ] push
    - [ ] reset
    - [ ] merge
---

### Start with an exisiting repo

You were surfing github and - while being absorbed in surfing - found an interesting repo. You really like this repo and wanna use it and continue developing it (you're super talented and have brilliant ideas).

You ask yourself, "how can I download this repo?"
Let me tell you, you have two options either download as zip or clone it (I prefer the second one)

> How to clone a repo?

```bash
git clone <repo link>
```

> Example: you liked this repo (start it). Yet, you think the repo lacks important details. So, you decide to clone my repo and enrich it with your knowledge (go ahead). First you clone it.

```bash
git clone https://github.com/Hagar-Usama/OhMyGit
```

Great! Now you have the repo cloned on your local machine. Now, you have a nice feature to add to this repo. You first try to add each commit directly to the main/master branch. But, you don't like the idea of a branchy master. You decide to create a new branch for this feature, add whatever commits, and lastly, merge it to the main branch with one commit. Nice, isn't it?

> How to create a branch?
```bash
git checkout -b <new-branch>
```

**-b** flag is for new branch, we will use checkout later for switching among different branches later

> Example: your new feature for my repo is to add some super notes for pull requests. So, you name it feature-pull-request

```bash
git checkout -b feature-pull-request
```
---

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