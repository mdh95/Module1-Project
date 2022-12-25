## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
    A version control system.
2. What is the difference between Git and GitHub?
    Git is a free and open source distributed code management and version control system. GitHub is a distributed version-control platform where users can collaborate on or adopt open source code projects, fork code, share ideas and more.
3. Why do we create a branch?
    These new branches can then be used to test changes to code without affecting the main project code. If the changes work, the branch can be merged back with the main branch.
4. What is the purpose of a Pull Request?
    A pull request is a way of notifying your team that you have work that needs to be reviewed. It’s a summary of your changes.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
    Git checkout "name of branch".
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
    Git fetch command is a reset to update a local repository to the state of a remote. The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch. Note that all of the commands presented below merge into the current branch.
7. What is a merge conflict?
    Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge.
8. How do you resolve a merge conflict?
    Under your repository name, click Pull requests.
    In the "Pull Requests" list, click the pull request with a merge conflict that you'd like to resolve.
    Near the bottom of your pull request, click Resolve conflicts.