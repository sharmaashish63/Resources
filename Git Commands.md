
# Git Commands

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.
If you are a developer and want to keep every version of your code/project (which you would most certainly want to), a Version Control System (VCS) is a very wise thing to use.

•	All the commands used for Git

•	Compatibility with GitHub





## Commands
### Set global username and email for Git (Locally).
	git config --global user.name "<your username>"

	git config --global user.email "<your email>"

### Initialise an empty Git Repository
    git init

### Clone an existing Git Repository

    git clone <repository URL>

### Add file/stage to git

    git add <filename>

### Add all the files to git

    git add .

### Commit all the staged files to git

    git commit -m "<your commit message>"

### Restore the file from being modified to Tracked

    git restore <filename>

    git checkout <filename>

### Show the status of your Git respository

    git status

### Create a new repository on the command line

    echo "# Resources" >> README.md

    git init

    git add README.md

    git commit -m "first commit"

    git branch -M main

    git remote add origin https://github.com/your repository name/Resources.git(URL of your github repository)

    git push -u origin main
