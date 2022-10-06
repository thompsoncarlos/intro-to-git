# Introduction to Git

## Git Structure
### Working Directory
- Area where all of our files directories and changes are living all the time.
### Staging Area
- Files and directories that we explicitly add to the staging area.
### Git Repository
- Where all our snapshots are stored.


## Git Adding, Removing and Ignoring

- Adding multiple files of a certain type
<code> git add *.html </code>

- Adding all files in directory (including hidden)
<code> git add -A </code>

- Removing files for staging area
<code> git reset HEAD <file> </code>

- Ignoring Files and Folders
1. Create .gitignore file to root directory
2. Add name of the files and folders do you want ignore

## Git Branches
 ```

   (feature1)     /-----0---0----0
                 /              / (merge feature1 to main)
(main)   0-----0-----0----0----0
```
  
- Listing all branches
<code>git branch</code>

- Adding a branch
<code>git checkout -b <branch_name></code>

- Changing branches
<code>git checkout <branch_name></code>

- Merging a branch
<code>git merge <branch_name></code>

- Removing a branch
<code>git branch -d <branch_name></code>

## Git and Github
1. Create or Login in Github
2. Create repository with the same name the local repository preferenced.
3. Add config remote origin repository to local repository
e.g. <code>git remote add origin  https://github.com/thompsoncarlos/intro-to-git.git</code>
Command to verify remote repository config
<code> git remote -v</code>
4. Push local repository to origin repository
<code> git push -u origin main</code>


