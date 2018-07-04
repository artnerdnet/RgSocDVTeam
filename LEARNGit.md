# **Learn** Git

_"Git is hard: screwing up is easy, and figuring out how to fix your mistakes is fucking impossible."_  

# Basic Git Commands


# TROUBLE SHOOTING

# list of __all git steps__, all branches, `index HEAD@{index}`:
`git reflog`

# find __last git step before its broken__:
`git reset HEAD@{index}`

# make change
`git add . #` or add individual files

# change or keep commit 
`git commit --amend`
- Last commit contains change

# create new branch from current state/master
`git branch some-new-branch-name`

# remove commit from master branch
- `git reset HEAD~ --hard`

# your commit lives in this branch now :)
- `git checkout some-new-branch-name`

# grab the last commit to master
- `git checkout name-of-the-correct-branch`
- `git cherry-pick master`
# delete it from master
- `git checkout master`
- `git reset HEAD~ --hard`

# Git won't do a diff of files add to staging area without this flag. 
- `git diff --staged`

# Resources

- [Github](https://try.github.io/)
- [Atlassian-Git](https://www.atlassian.com/git/tutorials)
- [Tower](https://www.git-tower.com/learn/)
- [OshitGit](http://ohshitgit.com/)
- [Learn Enough](https://www.learnenough.com/git-tutorial)
- [FreeCodeCamp](https://medium.freecodecamp.org/how-you-can-learn-git-and-github-while-youre-learning-to-code-7a592ea287ba)
- [Hackernoon](https://hackernoon.com/git-merge-vs-rebase-whats-the-diff-76413c117333)