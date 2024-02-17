## GIT COMMANDS!!!

### create a new repository on the command line
- echo "# Git-commands" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin <remote-url>
- git push -u origin main


### push an existing repository from the command line
- git remote add origin <remote-url>
- git branch -M main
- git push -u origin main

### Sub Commands
- git help -a / git help -g 				`git help`

- git status
- git branch / git branch -a
- git branch <brname>
- git checkout <brname>
- git fetch								    `get the updates from git repo`
- git pull								    - get the updates from git repo & merge it locally
- git remote show origin
- git remote -v
- git remote get-url origin				    - to get the origin details and set new origin
- git remote set-url origin <remote-url>
- git branch -d testfile2					- deleting branch locally
- git push origin -d testfile2			    - deleteing branch remotely
- git rm testfile2						    - removing file locally
- git commit -m "remove testfile2"		    - removing file remotely
- git push origin main
- git clone -b <brname> <remote-url>	    - Clone a Specific Branch