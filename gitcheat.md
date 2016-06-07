#Git Cheatsheet
**Name**: Joseph Bowling  
**Date**: 7 June 2016  

*Configuration commands*:

git config --global user.name "[name]"  
git config --global user.email "[email address]"  
git config --global core.editor "subl -n -w"  
git config --list  

*Adding, committing, and pushing*:

git add [filename]  
git commit -m "(message explaining change to the file)"  
git push [this command pushes the file to the GitHub repo]
git status [this command tells you want has been modified, tracked, and so on]  
  * git status -s [lists an abbreviated status update]  
git diff [this command shows changes made in a staged, but not committed, file]  