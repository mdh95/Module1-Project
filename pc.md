l## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is an Open Source Distributed Version Control System
2. What is the difference between Git and GitHub?
GitHub is a for-profit company that offers a cloud-based git hosting service.
3. Why do we create a branch?
A Git branch is essentially an independent line of development. You can take advantage of branching when working on new features or bug fixes because it isolates your work from other team members. In addition, different branches can be merged into any one branch as long as they belong to the same repository.
4. What is the purpose of a Pull Request?
Merging is git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by the git branch and integrate them into a single branch.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
Git Fetch is the command that tells the local repository that there are changes available in the remote repository without bringing the changes into the local repository. Git Pull on the other hand brings the copy of the remote directory changes into the local repository. Then git merge integrates them into a single branch.
7. What is a merge conflict?
Merge conflicts happen when you merge branches that have competing commit.
8. How do you resolve a merge conflict?
Create a new commit.