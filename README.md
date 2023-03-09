# how-to-git

This repository helps me to learn git commands and concepts

# Git Commands

Here are some useful git commands

## git config

It is a convenient way to set configuration options for your Git installation. You’ll typically only need to use this immediately after installing Git on a new development machine.

For example setting global email and username to your git configuration

```
git config --global user.name "your name"
git config --global user.email "your email"
```

## git init

Initializes a new Git repository. If you want to place a project under revision control, this is the first command you need to learn.

Basically is used to start a new repository

```
git init <path to the directory/folder>
```

or run `git init` to initialize git in current directory or folder

```
git init
```

## git clone

Creates a copy of an existing Git repository. Cloning is the most common way for developers to obtain a working copy of a central repository.

```
git clone <url to remote repository>
```

## git add

Moves changes from the working directory to the `staging area.` This gives you the opportunity to prepare a snapshot before committing it to the official history.

Basically it adds file or directory to the `staging area`

```
git add <directoryname/filename>
```

## git commit

Takes the staged `snapshot` and commits it to the project history. Combined with `git add`, this defines the basic workflow for all Git users. i.e it records or snapshots the file permanently in the version history.

Make sure to give descriptive commit messages

```
git commit -m 'descriptive message'
```
