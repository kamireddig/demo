#This is a DEMO Project that has GIT commands

git init demo
<Creates a repoistory named demo>

git status
<Checks the status of the repository we created>
	
mate README.md
<mate is a TextMate editor. Creating a file named README.md using mate command by TextMate, in the demo repository>

git add README.md
<add is a git command to add the file README.md into the staging area of the git repository>
	
git commit
<commit is a git command to commit the files in the staging area into the repository. It also creates a commit ID for every commit>
<-a parameter adds the files from the working directory into the staging area and commits into the Git repository as an express commit>
git log
<log is a git command that prints the last committed Author, Date and the commit message>
	
git show
<show is a git command that prints the Author, Date, commit message, file names and their commit ID's and the content of each file>
	
git ls-lart
<ls-lart is a git command to list all files that git keeps a track>

git reset HEAD <filename>
<the reset HEAD command is a git command used to remove the file from the staging area. Contents of the file will still be present in this file.>
	
git checkout -- <filename>
<the checkout -- command is a git command to revert the changes back to the last commited state. The contents of the file are removed in this stage>
	
git log --oneline --graph --decorate --all
<Creates a shorter version of the git log>
	
git config --global alias.hist "log --online --graph --decorate --all"
<Creates an alias for a command using the config command of git>

git <alias-name> -- <filename>
<running the alias for the filename only>
	
git mv <old-filename> <new-filename>
<mv is the git command to move or rename the file>
	
git checkout -b <branch-name>
<checkout is a git command that helps to move from branch to branch a branch and also creates one>
	
git merge <branch-name>
<merge is a git command that merges the branch and master>
	
git branch -d <branch-name>
<Deletes a branch>
	
git branch
<checks in which state we are currently in. Whether the branch or the master>
	
git tag <tag-name>
<creates a tag>
	
git tag --list
<lists out the available tags>
	
<<<<<<< Updated upstream
git stash list
<lists out all the stash available>
=======
git stash
<saves the last updated file as WIP (work in progress)>
>>>>>>> Stashed changes
