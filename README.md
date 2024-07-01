# Git Hub Cheat Sheet

Cheatsheet
This is a reference list of the most commonly used Git commands. (You might consider bookmarking this handy page.) Try to familiarize yourself with the commands so that you can eventually remember them all:

Commands related to a remote repository:

git clone git@github.com:USER-NAME/REPOSITORY-NAME.git

git push or git push origin main (Both accomplish the same goal in this context)

Commands related to the workflow:

git add .

git commit -m "A message describing what you have done to make this snapshot different"

Commands related to checking status or log history

git status

git log

The basic Git syntax is program | action | destination.

For example,

git add . is read as git | add | ., where the period represents everything in the current directory;

git commit -m "message" is read as git | commit -m | "message";

and

git status is read as git | status | (no destination).

Certainly! To push a new local branch to a remote Git repository and make it trackable, follow these steps:

First, create a local branch from another branch using either

 git branch or git checkout -b.

Next, commit your changes to the local branch.

Finally, push the local branch to the remote repository with the -u (or --set-upstream) option:

git push -u origin <branch>

Replace <branch> with the name of your branch.

Git will automatically set up the tracking information during the push.

For example, if you want to push a branch named “feature” to the “origin” remote, use:

git push origin feature

Remember to replace “feature” with your actual branch name. Happy coding! 😊🚀

for main branch use 

git checkout main

or 

git switch main
