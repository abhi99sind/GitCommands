# Git Commands



Hey saurabh here this is git commands

## Git commands to add file


1. git status --> showing chnages in your reository

2. git add <filename> --> shows my staging area

3. git commit --> take file from staging area and commit selected files

4. git log --> to check out history of chnages

5. git push --> to push your changes at selected branch (By default its master branch)

6. git difftool --> shows diffrence b/w your local changes and privious chnages



## Git commands to undo changes

#  Git commands to undo uncommitted changes

1. git checkout --<filename> --> for undo non commited text
2. git checkout --. --> to undo text from all files


#  Git commands to undo committed changes

1. git revert <git id> --> for undo committed changes


# Git commands to undo previous changes

1. git reset -hard <git id> --> To reset these above 


## How to make diffrent branch

1. git branch --> shows your branch
2. git branch <new branch name> --> creates new branch
3. git checkout <new branch name> --> it activates new branch


# Merging new branch to master branch

1. git checkout master --> switch to master branch
2. git merge <new branch name> --> merge your new branch to master branch
3. git push  --> add changes to your master branch


# Delete branch

1. git checkout <branch name> --> to activate your branch
2. git branch -d <branch name> --> to Delete your branch
