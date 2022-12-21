## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is an open-sourced version control system.

2. What is the difference between Git and GitHub?
GitHub is a hosting service that allows users to manage Git repositories.

3. Why do we create a branch? 
We use branches in order to isolate development work without affecting other branches in the repository.

4. What is the purpose of a Pull Request?
Pull requests allow you show changes you have pushed to others while comparing those changes to the original. this can all be done before finally actually merging the changes into the base branch.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout allows you to switch branches to a new branch. so if you wanted to go to the main branch you could use git checkout main

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
Git Fetch gets changes from a remote repo, git merge integrates those changes from the remote repo, and git pull does both at the same time.

7. What is a merge conflict?
A merge conflict happens when two branches are merged that have competing commits that are changing the same line.

8. How do you resolve a merge conflict?
you make a new commit where you decide which changes to incorporate from each conflicting branch.
