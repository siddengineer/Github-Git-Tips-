# 🧰 Git & GitHub Tricks and Tips

This repository is a comprehensive collection of essential Git commands, GitHub workflows, and collaboration techniques designed to help developers of all skill levels manage code versions effectively and work smoothly in teams.

## 🚀 What You'll Learn

- 📝 Core Git commands: commit, branch, merge, rebase, stash, and more
- 🔄 Branching strategies for efficient development
- 🛠️ Undoing mistakes with reset, revert, and reflog
- 🤝 Collaborating on GitHub: pull requests, code reviews, and issue tracking
- ⚡ Advanced GitHub features: Actions, Projects, Wikis, and GitHub Pages
- 💡 Time-saving Git aliases and best practices
- 📦 Managing releases and tags on GitHub

## 🎯 Who Is This For?

- Beginners getting started with Git and GitHub
- Developers improving their version control workflows
- Teams collaborating on open-source or private projects
- Anyone wanting to boost productivity using GitHub tools

## 📚 Sample Commands & Workflows

```bash
# Git basics
git clone <repo-url>
git branch
git checkout -b feature-branch
git add .
git commit -m "Add feature"
git push origin feature-branch

# Undo changes safely
git reset --soft HEAD~1
git stash save "WIP changes"
git stash apply

# GitHub collaboration
# Create a pull request (PR) from a feature branch to main/master
# Review and merge PRs via GitHub UI

# Sync fork with upstream repo
git remote add upstream <original-repo-url>
git fetch upstream
git merge upstream/main
git push origin main
