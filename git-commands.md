# Git Commands : 
## Git Setup

1. > git config user.name 

This command is used to define the global user name.

2. > git config -global

This command is used to define the global email of the user.

3. > git config color.ui auto

This command will give coloured output for git.

4. > git config merge.conflict style diff3

This command determines how the merge conflicts will be displayed.

5. > git config --list

This command is used to view all the configuration of the git.

6. > git config core.editor "path to editor"

This command sets the default git editor.

7. > git config init default Branch main

This command changes the default branch from master to main. 

## Repositories in Git

1. > git init

This command is used to make a folder a local repository.

2. > git status

This command is used to view the tracked and untracked files in the working area.

3. > git clone 'link to repo'

This command is used to mirror a particular repository from remote to local.

4. > git log

This command is used to view the previous changes in the repository / show all commits. 'q button to exit'.

5. > git log --oneline

This command is a shorter version of the git log command that shows only the commits.

6. > git log stat

This command gets the description regarding what files have been changed.

7. > git log --patch/-p 

This command is used to get much more detail on each commit. It gives the lines that were added/ Changed/ deleted.

8. > git show "commit id"

This command is used to view a particular commit.

## Doing Commits

1. > git add "file name"

This command is used to move the specific file from the working area to the staging area.

2. > git add .

This command is used to move all files from the working area to the stagging area.

3. > git commit -m "message"

This command is used write a message for each commit.

## Git Difference

1. > git diff

This command is used to view what changes has been done on the files that are added/removed.

## Git Restore

1. > git restore --staged "file name"

This command is used to remove the particular file from the staging area to working area / unstage a particular file from staging area to working area.

## Git Tagging

1. > git tag -a "tag name-v1.0.1" -m "message"

This command is used tp add a tag to the latest commit where -a stands for annotated tag.

2. > git tag

This command is used to view all the tags.

3. > git tag "tag name - v1.1.1" -m "message"

This command is used to create a light weight tag.

4. > git tag -d "tag name"

This command is used to delete a tag.


## Git Branching

1. > git branch

This command is used to view all the branches in the repo, and also see which is currently active.

2. > git branch "branch name"

This command is used to create a new brach. 

3. > git checkout "branch name" 

This command is used to switch to a specific branch.

4. > git branch -b "branch name" 

This command is used to create a new branch and directly switch to it.

5. > git switch "branch name"

This command is used to switch to a specific branch.

6. > git switch -c "branch name"

This command is used to create a new branch and directly switch to it.

7. > git branch -d "branch name"

This command is used to delete a branch.