# Brand new Project

## Dummy project for trying out git 

This project is used to try out github

Instructions 

Add git to a project 
```sh
git init  
```

Add files to the staging area
```sh
git add .
```

Make a Commit of files
```sh
git commit -m "Commit message"
```

check current branch 
```sh
git branch # check current branch 
git branch -a # show all branches
```

Add a remote repository 
```sh
git remote add <name> <url>
```

Push to remote repository
```sh
git push -u <name> <branch>
```

Working with branches 
```sh
git branch <newbranchname> # creates a new branch on the repo
git checkout <branchname> # this switches the branch in the working directory
```

Mergin Branches 
```sh
# merges <branchname> with active branch
git merge <branchname>
```
