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