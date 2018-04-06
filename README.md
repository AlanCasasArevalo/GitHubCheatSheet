# To start a GitHub Local repository:
- Use command `git init` to start a git local repository
- `git config --global user.name "Your name o nickname"` This command is used to show your name, to other people when these people show your repository
- `git config --global user.email "Your@email.com"` This command is used to show your email, to other people when these people show your repository

- `git config --global -e` This command show you the config of your repo information

- Create your .gitignore file (vi, nano, sublime text, etc)
- Add your files to ignore, like config files or files that you have to, you can use this webpage to do it: https://www.gitignore.io 

# To start a GitHub Remote repository:

- git init
- git add README.md
- git commit -m "your first commit"
- git remote add origin 'your remote gitHub or Bitbucket repository'  (https://github.com/AlanCasasArevalo/GitHubCheatSheet.git)
- git push -u origin master

# We are ready to start to work with git locally and remotely 

## To show stage area status:
- `git status` This command shows you all your files into stage area
- `git status -s` This command shows you all your files into stage area, with short information

## To add files to stage area we could use commands:
- `git add .` This command add all your files and folders into stage area
- `git add --all` This command add all your files and folders into stage area
- `git add -A` This command add all your files and folders into stage area
- `git add *.extensionToAdd` This command add all your files with specific extension in your folder into stage area
- `git add "*.extensionToAdd"` This command add all your files with specific extension stage area
- `git add FileToAdd` This command add specific file into stage area
- `git add FileToAdd FileToAdd` This command add specific file or files into stage area
- `git add folderToAdd/` This command add specific folder into stage area
- `git add folderToAdd/*.extensionToAdd` This command add specific extension folder into stage area
- `git add folderToAdd/ folderToAdd/` This command add specific folder or folders into stage area

## To commit when we want to, we could use commands:
- `git commit -m "Message to commit"`
- `git commit` This command open your default editor to write your custom commit

## To change a wrong commit you could do:
- `git commit --amend -m "Message to commit"` this commit just modify message commit anything else

- `git commit --amend` This command open your default editor to write your custom commit, this commit just modify message commit anything else

- `git commit -am "Message to commit"` This command add all your files to stage area and commit the changes into your default editor. 

- `git commit -am` This command add all your files to stage area and commit the changes


## To reset your work
- `git -- .` this command reset all work to before state, include if you delete all your work into trash

- `git checkout -- .` this command reset all work to before state, include if you delete all your work into trash

- `git reset --soft HEAD^` This command do a reset to an before state, but without files or folder modifications

- `git reset --soft (HASHLOG)` This command do a reset to an before state, but without files or folder modifications

- `git reset --hard (HASHLOG)` This command reset all work to before state modifing all files or folders

## To move into your repository
- `git mv "FileFromMoveOrRename" "FileToMoveOrRename"` this file move the file and rename the file if you want 

## To delete files or folders 
- `git rm "FileToDelete"` this command delete the file from stage area but to delete if necessary to commit

## To update files or folders
- `git add -u` This file update our file or folder but you have to commit if you want really update in repository

## To show before commits
- `git log` this command shows you before commits and you could move into them with HASHLOG
- `git log --oneline` this command shows you short description of before commits, and you could move into them with HASHLOG
- `git log --oneline --decorate --all --graph` this command shows you short description of before commits, and you could move into them with HASHLOG

- `git reglog` his command shows you before commits and you could move into them with HASHLOG in all times

## This is an example of hash commit

![](https://github.com/AlanCasasArevalo/GitHubCheatSheet/blob/master/commit-hash.png)

## To create global alias:
- `git config --global alias.lg "log --oneline --decorate --all --graph"` this command create an alias file alias.* and when we want to call ***git log --oneline --decorate --all --graph*** command we just to write `git lg`

## To know changes:
- `git diff` This command shows us changes between before eat 😜    for example 
- `git diff --staged` This command shows us changes between before go home 😜    for example 

## Branchs
- `git branch branchToCreate` This command create a new branch to work, and work do it in that branch is independent of master branch
- `git diff branchFromCheck branchToCheck` This command shows us difference between 2 branchs.
- `git merge branchToMerge` this command merge branch that we want to merge into current branch if the actual branch and branchToMerge have not conflicts between they, this is a Fast Forward, that means is not necessary to do anything special. 
- `git branch -d branchToDelete` This command delete branch that you want
- `git checkout -b branchToCreateAndToMove` This command create new branch and move HEAD to this new branch
## Tags
- `git tag` shows us all tags.
- `git tag TagToCreate` This command add new tag in repo
- `git tag -d TagToDelete` This command delete tag 
- `git tag -a vXXX -m "Message you want to add"` this command add a version and message, the version system is your choice













