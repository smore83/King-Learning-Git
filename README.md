3 way merging

Create a branch called greeting and switch to it
Edit the greeting.txt to contain your favorite greeting
Add greeting.txt files to the staging area
Commit
Switch back to the master branch
Create a file README.md with information about this repository
Add the README.md file to staging area and make the commit
What is the output of git log --oneline --graph --all?
Diff the branches
Merge the greeting branch into master
What is the output of git log --oneline --graph --all now? Observe the extra merge commit created with the message "Merge branch 'greeting'".
The task
In this kata git cannot figure out how to merge the content added on merge-conflict-branch1 with the content on master.

Both changes need to be in master when you're done.

Use git merge to bring the changes from merge-conflict-branch1 on to master.
What does git status now report.
Fix the conflict with your favorite editor.
Follow the instructions in git status to complete the merge.
What does git log --oneline --graph show?
Relevant commands
git merge
git status
git add
git commit
git log --oneline --graph