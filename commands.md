**git init** - Initializes a new Git repository.
```sh
git init
```
This command creates a new subdirectory named .git that contains all of your necessary repository files.

**git clone** - Clones a repository into a new directory. This command creates a copy of an existing repository in a new directory.
```sh
git clone https://github.com/username/repository.git
```

**git staus** - Displays the state of the working directory and the staging area. This command shows which changes have been staged, which haven’t, and which files aren’t being tracked by Git.
```sh
git status
```

**git add** - Adds file contents to the index (staging area). The first command stages a specific file, and the second stages all changes in the working directory.
```sh
git add filename
git add .
```

**git commit** - Records changes to the repository. This command commits the staged snapshot with a message describing the changes.
```sh
git commit -m "Commit message"
```

**git log** - Shows the commit logs. This command displays the commit history with details of each commit.
```sh
git log
```

**git branch** - Lists, creates, or deletes branches. The first command lists all branches, and the second command creates a new branch named `new-branch`.
```sh
git branch
git branch new-branch
```

**git checkout** - Switches branches or restores working tree files. The first command switches to an existing branch, and the second creates and switches to a new branch.
```sh
git checkout branch-name
git checkout -b new-branch
```

**git merge** - Joins two or more development histories together. This command merges the specified branch into the current branch.
```sh
git merge branch-name
```

**git remote** - Manages set of tracked repositories. The first command shows the URLs that a repository is tracking, and the second command adds a new remote repository.
```sh
git remote -v
git remote add origin https://github.com/username/repository.git
```

**git pull** - Fetches from and integrates with another repository or a local branch. This command fetches and merges changes from the remote repository's main branch into the current branch.
```sh
git pull origin main
```

**git push** - Updates remote refs along with associated objects. This command pushes the local branch `main` to the remote repository named `origin`.
```sh
git push origin main
```

**git ** - Shows the commit logs. This command displays the commit history with details of each commit.
```sh
git 
```