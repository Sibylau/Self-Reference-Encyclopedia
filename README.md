# Git command reference
## ssh without password
- between server and local
- between remote repo in git and local file

## branching
Reference: https://learngitbranching.js.org/
### basics
`$ git branch [branch_name]`  
Create a new branch pointing to the current commit, with branch name given by the parameter.  

`$ git merge [branch_name]`  
Stay in your own branch, and sync all changes from other branches (indicated by branch_name).  

`$ git rebase [branch_name]`  
Donate all commits (changes) in your own branch to other branches (indicated by branch_name).  

`$ git checkout [file/commit/branch_name]`  

