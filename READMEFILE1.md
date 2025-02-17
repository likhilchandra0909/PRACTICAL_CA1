## Git Commit States

Git tracks the changes you make to your files in different stages, allowing you to manage and review your work before committing it to the repository. The primary commit states are:

### 1. Untracked
- **Definition**: A file is in the "untracked" state when it exists in your working directory but hasn't been added to Git's tracking system yet.
- **How to identify**: You can see untracked files when you run `git status`. They will appear under the "Untracked files" section.
- **How to move it to the next state**: To start tracking the file, use the command:

### 2. Staged
- **Definition**: A file enters the "staged" state once you've added it to the staging area using `git add`. It means Git is ready to commit these changes, but they haven't been committed yet.
- **How to identify**: When you run `git status`, staged files will appear under the "Changes to be committed" section.
- **How to move it to the next state**: Once staged, you can commit the file using:


### 3. Committed
- **Definition**: A file is in the "committed" state when the changes you've staged have been saved into the local Git repository with a commit. This means the changes are now part of the project's history.
- **How to identify**: Committed files are no longer listed under `git status` since they are already recorded in the Git history. You can view your commit history with:
