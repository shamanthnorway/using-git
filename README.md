# Git Commands

Use Git commands to help keep track of changes made to a project:

* **git init:** creates a new Git repository
* **git status:** inspects the contents of the working directory and staging area
* **git add:** adds files from the working directory to the staging area
* **git diff:** shows the difference between the working directory and the staging area
* **git commit:** permanently stores file changes from the staging area in the repository
* **git log:** shows a list of all previous commits
* **git checkout HEAD _filename_:** Discards changes in the working directory.
* **git reset HEAD _filename_:** Unstages file changes in the staging area.
* **git reset SHA:** Can be used to reset to a previous commit in your commit history.
* **git branch:** Lists all a Git project's branches.
* **git branch _branch_name_:** Creates a new branch.
* **git checkout _branch_name_:** Used to switch from one branch to another.
* **git merge _branch_name_:** Used to join file changes from one branch to another.
* **git branch -d _branch_name_:** Deletes the branch specified.

### Creating a new git
```
git init
// edit .gitignore
git add *
git status
git commit -m "some message"

git remote add origin "URL"
git remote -v

git push origin master
```