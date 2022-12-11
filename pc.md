## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
Git is an open source version control system, or VCS for short.

2. What is the difference between Git and GitHub? 
Git is the VCS, while GitHub is simply the repository where files are stored and shared.

3. Why do we create a branch? 
A branch is created so an individual can edit a document locally on their computer before sharing it/pushing it to the shared GitHub repository.

4. What is the purpose of a Pull Request?
A pull request lets you tell others about changes you have pushed to a branch in a repository on GitHub.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout -b 'BRANCH' would let you switch between branches. To switch to the main branch you would enter:
git checkout -b 'main'

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git fetch retrieves new work done by other people. when you fetch a repository it grabs all the new remote-tracking branches and tags without merging those changes into your branch

git merge combines your local changes with changes made by others

git pull is simply the combination of both git fetch and git merge into one command

7. What is a merge conflict?

A merge conflict occurs when competing changes are made to the same line of a file, or when someone edits a file that another person has deleted.

8. How do you resolve a merge conflict?
To resolve a merge conflict caused by competing changes to a line, you must choose which changes are actually incorporated in a new commit.
When the merge conflict is caused by a deleted file, you must choose whether to delete or keep said file in a new commit.