# learning-path-dashboard
Learning Path Dashboard Web App with progress tracking

To update changes to Git from local repository (if forgotten to pull beforehand) follow these steps:
(Run these commands in terminal in VSCode in the project folder)
1. Check your current git status \n
   Run command: git status
   This will show you which files have been modified and need to be committed.

2. Pull Latest Changes
   Before you commit, you'll want to pull the latest changes from the remote repository. However, since you haven't updated Git yet and want to avoid any merge conflicts, first stash your local changes.
   Run command: git stash
   
3. Pull Changes from the Remote Repository
   Run command: git pull origin main

4. Apply Your Stashed Changes
   Run command: git stash pop
   
5. Add and Commit Your Changes
   Run commands:
   git add .
   git commit -m "Your commit message"

6. Push Your Changes (back to remote repository)
   Run command: git push origin main
   This ensures that your local changes are safely added

