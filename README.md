# sdh-itad

## 📌 Overview
This repository follows a **branch-based development workflow**.  
All changes, updates, and new features must be made in separate branches before being merged into the main branch.

---

## 🚀 Branching Workflow
1. Create a new branch for each change/feature:
   ```bash
   git checkout -b feature/your-feature-name//

LEARN IMPORTANT COMMANDS 
#commands
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --list       # Check config
🔹 Getting Started(important)
git init                # Initialize a new repository
git clone <url>         # Clone a repo
🔹 Basic Snapshotting(important )
git status              # Check status
git add <file>          # Stage file
git add .               # Stage all changes
git commit -m "message" # Commit staged changes

🔹 Branching & Merging(important)
git branch              # List branches
git branch <name>       # Create branch
git checkout <name>     # Switch branch
git checkout -b <name>  # Create + switch branch
git merge <branch>      # Merge branch into current
git branch -d <name>    # Delete branch

🔹 Remote Repositories(important)
git remote -v                           # Show remotes
git remote add origin <url>             # Add remote
git push -u origin <branch>             # Push first time
git push                                # Push changes
git pull                                # Fetch + merge changes
git fetch                               # Fetch changes only
git clone <url>                         # Clone repository

🔹 Undoing Changes
git restore <file>                      # Undo unstaged changes
git reset <file>                        # Unstage file
git reset --hard                        # Reset to last commit (dangerous!)
git revert <commit>                     # Undo specific commit safely

🔹 Stashing
git stash                               # Save changes temporarily
git stash list                          # Show stashes
git stash apply                         # Reapply last stash
git stash drop                          # Delete last stash

🔹 Logs & History
git log                                 # Commit history
git log --oneline --graph --decorate    # Pretty log
git diff                                # Show unstaged changes
git diff --staged                       # Show staged changes

🔹 Tags
git tag                                 # List tags
git tag <name>                          # Create tag
git push origin <tag>                   # Push tag
