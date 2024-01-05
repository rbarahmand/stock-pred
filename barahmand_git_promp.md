# Reza Barahmand - Code 16 - git final project prompts

## Problem 1 (Question)

- Create a git repo and add some files from an existing project.
- Add files to git and commit them.
- Write a meaning full comment for the the commit process.
- Edit previous commit comment.

## Problem 1 (Answer)

Navigating to the directory:

```sh
ls
cd "Data Science Class"
ls
cd "15 - Git"
mkdir git_project
cd git_project
ls
```

Create a git repo and add some files to it:

```sh
git init
code README.md
code tele_bot.py
code insertion_sort.py
```

Adding files to the git and commit them with a meaningful comment:

```sh
git add -A
git status
git config --global core.editor "'C:\Program Files\Sublime Text/sublime_text.exe' -w"
git commit
git status
```

Changing the previous commit message:

```sh
git commit amend
git log
```

Adding the given files to the project and commit them:

```sh
git status
git commit
git log
```

Deleting the given files due to large size, in order to upload it:

```sh
del files
ls
git status
git commit
git log
```

## Problem 2 (Question)

- Create an empty repo on github.
- Clone an arbitrary repository on github.
- Define a remote for the previously cloned repo and connect it to your github acc.

## Problem 2 (Answer)

Navigating to a new directory:

```sh
cd ..
mkdir github_project
cd github_project
```

Cloning a repo (Stock market prediction using deep NN)\
here I use `gh` which is `github-cli`

```sh
gh repo clone achillesrasquinha/bulbea
gh ls
```

Initialization of git on this project

```sh
git init
git commit
git status
git log
```

Add a remote for this repo and connecting it to my github acc.\
here I use `gh` which is `github-cli`\
For further use of github-cli check out it's [documentation](https://cli.github.com/manual/).

```sh
github_project git(master) gh repo create stock-pred --public --source=. --remote=upstream
git push --set-upstream upstream master
```

Adding a README file for the public clone of the repo

```sh
code README.md
git status
git add -A
git commit
git push
```
