
## Git Self Help

#### Check Git Version
```
git --version
```
#### Git user Config
```
git config --global user.name "Sateesh"

git config --global user.email "sateeshnaidu900@gmail.com"

git config --global --list

git clone https://gitlab.com/gitlab-tests/sample-project.git
```
#### Git Clone via SSH
```
git clone git@gitlab.com:gitlab-org/gitlab.git
```
#### Convert a local directory into a repository
```
git init
```
#### Add a remote repository
```
git remote add origin git@gitlab.com:username/projectpath.git
```
#### Download the latest changes in the project
```
git pull <REMOTE> <name-of-branch>
```
#### View your remote repositories
```
git remote -v
```
#### Create a branch
```
git checkout -b <name-of-branch>
```
#### Switch to the master branch
```
git checkout master
```
##### Work on an existing branch
```
git checkout <name-of-branch>
```
#### View the changes you’ve made
```
git status
```
#### View differences
```
git diff
```
#### Add and commit local changes
```
git add <file-name OR folder-name>
git commit -m "COMMENT TO DESCRIBE THE INTENTION OF THE COMMIT"
```
#### Add all changes to commit
```
git add .
git commit -m "COMMENT TO DESCRIBE THE INTENTION OF THE COMMIT"
```
#### Send changes to Git
```
git push <remote> <name-of-branch>
git push origin master
```
#### Delete all changes in the branch
```
git checkout .
```
#### Unstage all changes that have been added to the staging area
```
git reset .
```
#### Undo most recent commit
```
git reset HEAD~1
```
#### Merge a branch with master branch
```
git checkout <name-of-branch>
git merge master
```
[Content Source](https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html)


