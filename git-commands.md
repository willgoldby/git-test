# git tag
Adds tags to a branch. A tag describes a commit. For example, by specifying a version, like v1.0.2.


comment made on main 1

# git checkout -b branch-name
Creates a new branch and moves HEAD to that branch.

# git merge branch-name-you-want-to-merge
Adds the commits from the branch you name onto the branch you're in.

# git log --oneline
Prints out the commit history, line by line.

# git branch -v
Lists the last commit for each branch.

comment made on main 2
# git branch --merged
List the branches merged into the current branch.

# git branch --no-merged
List branches not merged into the current branch. 

# git remote show <remote>
List information about the remote branch or branches.

# git rebase <the branch you want to integrate into the one you're on>
Integrates changes from another branch to the one you're on. Instead of making a new merge commit, it takes the unique commits from your current branch and replays them on top of the latest commit from the other branch (the one you are rebasing onto). This changes the base commit of your current branch, making it appear as if you started your work from the latest point of the other branch
