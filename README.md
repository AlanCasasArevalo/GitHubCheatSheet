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
- `git status`

## To add files to stage area we could use commands:
- `git add .` This command add all your files or folders into stage area
- `git add FileToAdd` This command add specific file into stage area
- `git add FileToAdd FileToAdd` This command add specific file or files into stage area
- `git add folderToAdd/` This command add specific folder into stage area
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

## To show before commits
- `git log` this command shows you before commits and you could move into them with HASHLOG
















