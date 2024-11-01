#### Core Commands
**git init** - Initializes a new, empty Git repository in the current directory. This command creates a new subdirectory named .git that contains all of your necessary repository files.
```sh
git init
```

**git clone** - Creates a local copy of a remote repository. This command creates a copy of an existing repository in a new directory.
```sh
git clone https://github.com/username/repository.git
```

**git add** - Stages a specific file or all changes in the directory (with `.`) for the next commit. The first command stages a specific file, and the second stages all changes in the working directory.
```sh
git add filename
git add .
```

**git commit** - Commits staged changes with a descriptive message. This command commits the staged snapshot with a message describing the changes.
```sh
git commit -m "Commit message"
```

**git staus** - Displays the state of the working directory and the staging area. This command shows which changes have been staged, which haven’t, and which files aren’t being tracked by Git.
```sh
git status
```

**git diff** - Shows changes between the working directory and the staging area. To compare branches, use:
```sh
git diff
git diff branch1 branch2
```

**git checkout** - Switches to specific branches or to the `main` branch. The first command switches to an existing branch, and the second creates and switches to a new branch.
```sh
git checkout branch-name
git checkout -b new-branch
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



**git stash** - Stashes changes in the working directory. The first command stashes the current changes, and the second applies the stashed changes back to the working directory.
```sh
git stash
git stash pop
```

**git rebase** - Reapplies commits on top of another base tip. This command rebases the current branch onto `branch-name`.
```sh
git rebase branch-name
```

**git resets** - Resets current HEAD to the specified state. The first command moves HEAD to the previous commit but keeps changes staged, while the second command moves HEAD to the previous commit and discards all changes.
```sh
git reset --soft HEAD~1
git reset --hard HEAD~1
```

**git fetch** - Downloads objects and refs from another repository. This command fetches updates from the remote repository named origin without merging them into the current branch.
```sh
git fetch origin
```

**git cherry-pick** - Applies the changes introduced by some existing commits. This command applies the changes from the commit with the specified hash to the current branch.
```sh
git cherry-pick commit-hash 
```

**git revert** - Reverts a commit by creating a new commit that undoes the changes. This command creates a new commit that reverses the changes made by the specified commit.
```sh
git revert commit-hash
```

**git tag** - Creates, lists, deletes, or verifies a tag object signed with GPG. The first command lists all tags, the second creates an annotated tag `v1.0` with a message, and the third deletes the tag `v1.0`.
```sh
git tag
git tag -a v1.0 -m "Version 1.0"
git tag -d v1.0
```

**git ** - Shows the commit logs. This command displays the commit history with details of each commit.
```sh
git 
```

**git ** - Shows the commit logs. This command displays the commit history with details of each commit.
```sh
git 
```

**git ** - Shows the commit logs. This command displays the commit history with details of each commit.
```sh
git 
```

**git ** - Shows the commit logs. This command displays the commit history with details of each commit.
```sh
git 
```

**git ** - Shows the commit logs. This command displays the commit history with details of each commit.
```sh
git 
```

**git ** - Shows the commit logs. This command displays the commit history with details of each commit.
```sh
git 
```

**git ** - Shows the commit logs. This command displays the commit history with details of each commit.
```sh
git 
```

**git ** - Shows the commit logs. This command displays the commit history with details of each commit.
```sh
git 
```