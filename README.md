# What is Git?

A free and open source version control system. Version control is a management of changes to documents, programs, and other information. It is used to understand what we did when, track down bugs and go back to previous versions.

# Major commands in Git

1) Clone
2) Add
3) Commit
4) Push
5) Pull

# Git Initialization

Initializes a new repository
<br/>
Command : ``` git init ```

# Create connection

Create a connection between local repository and remote repository
<br/>
Command : ```git remote add origin "https://github...." ```

# Cloning a Git repository

Bring a repository into a folder in your local machine
<br/>
Command : ```git clone git@github.com:gwef/demo-repo.git```

# Add/Stage the file

Track down the file and changes in git
<br/>
Command : ```git add .```  // for adding all files
<br/>
Command : ```git add index.html```  // for adding index.html file

# Commit file

Save the file in git
<br/>
Command : ```git commit -m "added new task"```

# Push

Upload git commits to remote repository
<br/>
Command : ```git push -u origin main```

# Branches

1) Master branch or Main branch
2) Feature branch or Test branch

## Create new branch

Command : ```git checkout -b test```

## Steps to add this new branch to main branch

1) Add/Stage file
2) Commit test branch
3) Switch to main branch .Command : git checkout main
4) Merge branch .Command : git merge test

# Undo operation

Command : ```git reset```

## Undo commits

Command : ```git reset HEAD~1```

## Goto particular commit without changes on main file

Commands : ```git reset hash. Hash is the unique no with every commits done.```

## Goto particular commits with changes on main file

Command : ```git reset --hard hash```

# Fork

Copy repo of others code to our online repo
