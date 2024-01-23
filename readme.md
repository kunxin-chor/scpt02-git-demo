# Git Workflow Commands

## Seeing changes
* `git status`: Show all the files that have been changed. If any files is shown as `untracked` it means it haven't been in Git before (usually new files).

## Staging Files
* To stage, use `git add <filename>`
* To stage all changes, use `git add .`

## Commit 
* `git commit -m "<commit message>"`

## Branch
* Use `git branch <new-branch-name>` to create a new branch
* Use `git checkout <new-branch-name>` to go to a different branch
* Use `git checkout -b <new-branch-name>` to create a new branch and switch to it immediately