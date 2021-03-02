# Read: 02b - Revisions and the Cloud

## Version Control
""is a system that allows you to revisit various versions of a file or set of files by recording changes""

"Every single change applied to any file or directory is tracked by Git"

states

Git files could be found in three states:

1. Committed:Data is securely stored in a local database.

2. Modified:File has been changed but not committed to the database.

3. Stages:Flagged a file’s changed version to be committed in the next snapshot. 

![1a](https://i.morioh.com/2019/11/11/1f265e2d4c43.jpg)



# Local Repository Structure The local Git repository has three components:

* Working Directory: The actual files reside here.
* Index: The area used for staging
* Head: Points to the most recent commit 

Pushing Changes

# For exporting and pushing the changes to a remote repository, so others can see it, use the following command: $ git push origin master

## Stashing Changes

### Use: Git Stash to temporarily removes changes and hides them, giving you a clean working directory. and When you are ready to continue working on the changes, simply use the git stash apply command to retrieve the hidden changes.
