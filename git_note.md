# Git Note
## config
git config --global user.name <name>
git config --global user.email <email>
git config --global core.editor "code --wait"
git config --global -e: edit all global setting
* mac: git config --global core.autocrlf input
* window: git config --global core.autocrlf true
* for help: git config on google or git config --help/ -h

## Create repostory:

* git init
* show folder: ls -a





git clone <url>: download


git diff: see change


git add <filename>: make a change, everytime before commit
* git add . --> add all file in folder
* git add *.txt: add all file txt

git commit -m "message": message for change above
git commit -am "message": add & message in the same time.

git status: get information now

git push: to push online

git pull: get changed file from online

(if some merge conflict happen: just choose one then commit and push again)

git log: see history 

git reset: (should use git log to find the commit)
    git reset --hard <commit>
    git reset --hard origin/master

branching:
git branch; show all brannch
    git branch <branch name>: create new branch
    git checkout <branch name>: switch to new branch


git merge:
    example: git merge tests
    git branch -D tests: delete branch