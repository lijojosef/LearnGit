## What is Git & Github?
Allows us to maintain the history of the project. 

## Some basic linux commmands:
ls: list
mkdir: make directory
cd: change directory

## Initializing the git
git init

## How to check whether our codes are committed or not?
git status

## Add all
git add .

## Commit
git commit -m "comment"

## To restore the added one
git restore --staged filename.extension

## to check the logs
git log

## removing a commit from the history of the project
git reset HASH_ID 

## Stashing the changes
git stash

## Poping the stash
git stash pop

## Clearing stash
git stash clear

## Connecting to the repository
- Create a repository in gitHub
- git remote add origin LINK
- git remote -v (to see all the branches)

## connection 
git push origin master

## Authenticating git remote
https://statistics.berkeley.edu/computing/faqs/git-auth

## Generating tokens
https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token

## Branches
git branch BRANCH_NAME

## Switching to the new branch
git checkout BRANCH_NAME

## Merging the new branch to the main branch
git merge BRANCH_NAME

# Working with existing projects
## Cloning the project
git clone URL

## Adding upstream - To take a pull request from the main link where you've forked
git remote add upstream URL


