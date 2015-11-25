##Git User Basics
###Git Levels
* System (All Users: /etc/.gitconfig)
* Global (User: ~/.git)
* Local (Per Repository= a directory: .git)
###Git Configuration Commands
git config  --global user.name 
git config  --global user.email
git config  --global user.password
git config -l (shows all config entries)
git config --global color.ui true	

###Create local Repository
* git init (in a local directory)
* touch readme.md .gitignore
* creates a .git subdirectory in directory where git init was issued
* create a file, add content
* git add "file | directory | regex | . (all)"
* git commit -m "Add a commit message"
* git push
###Ignore for Git Tracking
* create .gitigonore
* add directories to .gitignore (list files or directories line by line, regex possible)
###Git Concepts
Git is a distributes Version Control System.
####Distributed
When you clone you get the full history and version of the code.
Most version control systems give you the latest version.
Git has no central repository because each user has a full version locally.
Every time you push or clone a repository you make a backup.
###Working Directory (your directory)
Working Directory holds the checkout of the last commit.
Uncompressed last files where your changes are going to be done.
The WD is the place where you can hold changes you do not want already
commit.
###Staging Area (git index)

###Repository

###Commit
The way how Git stores "snapshots of changes". It is a set of changes
identified with a sha hash. Every Commit points to its parent commit.
A merge (merge of two branches has 2 parents)
![Git Commit](img/git-commit-diagram.png)

###Git Database
* files (Blob: git stores file content in a blob)
* directories

###Git References
* SHA-1 Hash
* Branches
* HEAD
* Ancestor References (Parent:HEAD~, Grand-Parent:HEAD~2, Grand-Grand-Parent:HEAD~3,...)
* ![Git References Diagram](img/git-references.png)

###Git Object Types Blob and Tree
* Blob (identified by a sha hash)
header information and 
* Tree (hashed

###Commit Message

###HEAD
Git Reference to the head of branch of your last commit. It is like the
recording head of a tape recorder positioned at the head where the new
reocording will go

###Branch

###Master

###Origin


###Git Logs and Branches

###Github and Remotes

###Intermediate Usage

###Git Diff Tool
