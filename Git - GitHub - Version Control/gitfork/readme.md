### Branching 
---

What is Branching?

- This lets us create side branches that lets us create experimental features or branches.
- This lets us have a main BRANCH and Experimental
- Sometimes we want to MERGE the experimental changes to the main project, this is why we have MERGE.


1. First lets go back to our Story directory and add a branch "alien-plot"
2. Type git branch to view current branch were on and all branches
3. To Switch branches we need to check it out. // git checkout alien-plot
4. Now we can make changes to our Story, doesn't need to be anything.
5. Now lets add and commit to this new branch
6. If we do a git log we can see our commits are now on the master branch and also alien plot
7. Git Checkout Main or Alien-plot will automatically modify the local branch files.
8. Lets switch back to Main and merge alien-plot now that we want the new features added. VIM WILL OPEN
    - :q! to save and quit



###  Forking
---

What is Forking?
    - This Lets us collaborate  with others without fear of messing up the main repository. 
    - This is different than cloning as it makes a copy of the repo but you have FULL permsissions to make changes. 
    - Once its forked to your github, then we can clone it to the local repo and make changes.
    - From there we can push it to our remote repo aka github forked repo and if you think the original would be better with your features you can create a pull request. Its like a suggestion, they don't have to accept your changes.
    - It's called pull request because we don't own the rights to the repo were trying to push to. 
    - If the author approves the pull request and  they merge the changes then the update is complete.