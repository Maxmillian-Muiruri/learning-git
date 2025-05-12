# Git and GitHub Documentation

## What is Git?

Git is a distributed version control system that allows developers to track changes in their source code during software development. It helps multiple developers collaborate on a project by managing changes and maintaining a history of modifications.

## What is GitHub?

GitHub is a web-based platform that hosts Git repositories. It provides a user-friendly interface for managing Git repositories, collaborating with others, reviewing code, and integrating with other tools and services.

## Common Git Commands

- `git init`  
  Initializes a new Git repository in the current directory.

- `git add <file>`  
  Adds changes in the specified file(s) to the staging area, preparing them to be committed.

- `git commit -m "message"`  
  Records the staged changes to the repository with a descriptive message.

- `git push`  
  Uploads local repository content to a remote repository, such as GitHub.

- `git merge <branch>`  
  Combines the changes from the specified branch into the current branch.

- `git squash`  
  Squashing is the process of combining multiple commits into a single commit, often done during rebasing to keep a clean commit history.

## Advanced Git and GitHub Commands

- `git clone <repository-url>`  
  Creates a local copy of a remote repository.

- `git fetch`  
  Downloads objects and refs from another repository without merging.

- `git pull`  
  Fetches from a remote repository and merges into the current branch.

- `git branch`  
  Lists, creates, or deletes branches.

- `git checkout <branch>`  
  Switches to the specified branch or restores working tree files.

- `git rebase <branch>`  
  Reapplies commits on top of another base tip, useful for a cleaner history.

- `git reset <commit>`  
  Resets current HEAD to the specified state, can be used to unstage or discard changes.

- `git log`  
  Shows the commit history for the current branch.

- `git remote`  
  Manages set of tracked repositories. For example, to add a GitHub repository as a remote, use:  
  `git remote add origin https://github.com/username/repository.git`

## Additional Resources

- [Git Official Documentation](https://git-scm.com/doc)
- [GitHub Learning](https://skills.github.com/)

## Author

Maxmillin
