**git init** - Initializes a new Git repository. This command creates a new subdirectory named .git that contains all of your necessary repository files.
```sh
git init
```

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