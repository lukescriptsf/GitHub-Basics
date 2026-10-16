# GitHub-Basics

Welcome to my `GitHub-Basics` repository!

This project serves as my personal cheat sheet and memory aid for working with Git and GitHub. It documents the most important commands, everyday workflows, and configurations I need for my software development projects.

## 🔄 The Daily Workflow

These are the commands I use every time I make changes to my code and want to upload them:

1. **Check the current status:**
   ```bash
   git status
   ```

2. **Add changes to the staging area:**
   ```bash
   git add .
   ```

3. **Save the changes locally (Commit):**
   ```bash
   git commit -m "Describe the changes made"
   ```

4. **Upload the commit to GitHub (Push):**
   ```bash
   git push
   ```

5. **Download the latest changes from GitHub (Pull):**
   ```bash
   git pull
   ```

## 🚀 Starting a New Project

When creating a brand-new local project and connecting it to a fresh (empty) GitHub repository:

```bash
# 1. Initialize Git in the local folder
git init

# 2. Add and commit the initial files
git add .
git commit -m "Initial commit"

# 3. Connect to the remote GitHub repository
git remote add origin https://github.com/lukescriptsf/Your-Repo-Name.git

# 4. Push for the very first time
git push -u origin main
```

## 🛠️ Helpful Commands

* **`git log`**: View the commit history (press `q` to exit).
* **`git branch`**: List all local branches.
* **`git restore <file>`**: Discard uncommitted changes in a specific file.

## 📝 .gitignore

The `.gitignore` file is crucial. It tells Git which files or folders should *never* be tracked or uploaded (e.g., passwords, API keys, `.DS_Store` on macOS, or virtual environments like `.venv/`).
