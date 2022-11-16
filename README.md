## Cloning a Github epository

`git clone git@github.com:mochen862/git-commands.git` - cloning repository

`git status`

`git add .` - track all the files

`git commit -m "First message" -m "some description"`

`git push -u origin main`

## Initialise a repository locally and push it to Github

cd into the local repository

`git init`

`git status`

`git add .`

`git commit -m "some message" -m "some decription"`

`git branch -M main`

`git remote add origin git@github.com:mochen862/git-commands.git`

`git remote -v` - to check any remote repositories that this repo is connected to

`git push -u origin main`

## Git branching

`git branch` - to see which branch you're on

`git checkout -b feature` - to create new branch

`git checkout` - to switch between branches

`git checkout main` - switching to main branch

`git diff feature` - shows the differences

`git push -u feature` - pushing feature branch to Github

use Github UI to create a pull request - merge the pull request - locall switch to main branch

`git checkout main`

`git pull -u origin main`

`git branch -d feature` - delete feature branch that we no longer need

## Undoing in Git

`git reset` - to unstage changes

`git reset HEAD~1` - point to last commit and go back one commit further (unstaged and uncommitted)

`git log` - log in reverse chronological order

`git reset bbab839296459e0561b3a1fd5faa4d10c4ad5670` - copy one of the hashes to go back to a specific change

`git reset --hard bbab839296459e0561b3a1fd5faa4d10c4ad5670` - get rid of all changes after a certain point (not just unstaged, but completely removed)