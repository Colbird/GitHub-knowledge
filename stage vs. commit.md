 To stage a file is simply to **prepare it finely for a commit**. Git, with its index allows you to commit only certain parts of the changes you've done since the last commit. Say you're working on two features - one is finished, and one still needs some work done. You'd like to make a commit and go home (5 o'clock, finally!) but wouldn't like to commit the parts of the second feature, which is not done yet. You stage the parts you know belong to the first feature, and commit. Now your commit is your project with the first feature done, while the second is still in work-in-progress in your working directory.
**Fetch**: Will get all new and changed branches into the locally repository using the tracking branches (e.g. origin/) *git branch --remote* to list the tracking branches and *git checkout [branch]* to actually switch to any given one.
**Pull**:
**Push**:
**Sync**:
**Pop**:  More
**Stash**: Place to hide modifications whe working on something else
**Branch**: Branches allow you to preserve the main code (the 'master' branch), make a copy (a new branch) and then work within that new branch. Merging or rebasing (often preferred for better history and easier to resolve conflicts) against the master branch should be done often if Master changes. Two main approaches to doing branches: (1) only using branches for larger and longer-running things like version changes. (2) make a branch for every feature request, bug fix or chore and then manually decide when to actually merge those branches into the main master branch *Reccomended* keeps master branch cleaner.
**Fork**: Fork: With a branch you control and manage the branch, whereas with a fork someone else controls accepting the code back in. other approach - forking - allows anybody to 'fork' the repository, basically making a local copy in their own git repository account. They can then make changes and when finished send a 'pull request' (really it's more of a 'push' from them and a 'pull' request for the actual repository maintainer) to get the code accepted.
This second method, using forks, *does not [Unlike Merging] require someone to maintain a list of users for the repository*. 

**Merge**: way to bring a branch "in" to master
**Rebase**: get new master and see how you branch works before *merging*
**Clone** copy of repository. This clone has everything, the files, the master branch, the other branches, all the existing commits.

Need to fix this tooo
