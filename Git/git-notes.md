### ✅ Setup (once per system or project)

    git config --global user.name "Reymond Joaquin"
    git config --global user.email "your_email@example.com"

### 📁 Start a Git Project

    git init                # Create a new Git repo in current folder
    git clone <url>         # Clone an existing repo from GitHub

### 📄 Tracking Changes

    git status              # Show current status of files (tracked/untracked)
    git add .               # Stage ALL modified & new files
    git add <file>          # Stage specific file(s)
    git commit -m "message" # Commit staged files with a message

### 🔁 Update Remote Repository (Push to GitHub)

    git remote add origin <repo-url>  # Link local repo to GitHub (only once)
    git branch -M main                # Rename branch to main (if not yet)
    git push -u origin main           # First push (sets upstream)
    git push                          # Push new commits to GitHub

### 🔄 Get Updates from GitHub

    git pull                          # Fetch + merge changes from GitHub
    git fetch                         # Only fetch (no auto-merge)

### 🧹 Fixes and Undo

    git restore <file>               # Undo local changes (before commit)
    git reset HEAD <file>            # Unstage a file (after `git add`)
    git log                          # View commit history

### 🌿 Working with Branches (if needed in future)

    git branch                       # List branches
    git checkout -b <branch-name>    # Create and switch to new branch
    git checkout main                # Switch back to main
    git merge <branch-name>          # Merge a branch into current

### 🧠 Check current branch
    git branch

### 📝 Git Tag Cheat Sheet:

    # List tags
    git tag

    # Create tag with message
    git tag -a v1.2.0 -m "Add Auto-Guard feature and zombie fix"

    # Push tag to GitHub
    git push origin v1.2.0

    # Delete local tag (if needed)
    git tag -d v1.2.0

    # Delete remote tag (if needed)
    git push origin --delete v1.2.0


