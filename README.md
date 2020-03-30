# Git command reference
## ssh without password
- between server and local
- between remote repo in git and local file

## branching
Reference: https://learngitbranching.js.org/  
https://www.atlassian.com/git/tutorials/using-branches/git-checkout  
https://guide.freecodecamp.org/git/git-checkout/  

### basics
`$ git branch`  
List all branch names  

`$ git branch <branch_name>`  
Create a new branch pointing to the current commit, with branch name given by the parameter.  

`$ git merge <branch_name>`  
Stay in your own branch, and sync all changes from other branches (indicated by branch_name).  

`$ git rebase <branch_name>`  
Donate all commits (changes) in your own branch to other branches (indicated by branch_name).  

`$ git checkout <commit_id/branch_name>`
Go to the specific commit or existing branch.

`$ git checkout -b <new_branch_name>`
Create and jump to that branch.

`$ git checkout <commit_id/branch_name>`

`$ git log`
View commit history

`$ git `

