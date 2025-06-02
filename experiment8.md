# Experiment 8 – Display Last Five Commits in Git

## Objective:
Write the command to display the last five commits in the repository’s history.

## Commands Used:
- git log --oneline -n 5
- git log -n 5 --pretty=format:"%h - %an, %ar : %s"

## Sample Output:
a1b2c3d - Alice, 2 hours ago : Fixed login bug  
e4f5g6h - Bob, 1 day ago : Updated README  
i7j8k9l - Alice, 3 days ago : Refactored auth flow
