
# Git & GitHub for Web Developers — Week 1 Day 5

## 📌 Overview

This project demonstrates essential Git and GitHub workflows used in professional web development, including feature branching, commits, pull requests, interactive rebasing, `.gitignore`, and merge conflict resolution.

## 🎯 Objectives

- Understand Git branching and collaboration workflows.
- Create and manage feature branches.
- Write descriptive commit messages.
- Squash multiple commits using interactive rebase.
- Create a professional pull request with a review checklist.
- Configure `.gitignore` for a Node.js project.
- Simulate and resolve merge conflicts.

## 🛠️ Tools & Technologies

- Git
- GitHub
- Visual Studio Code
- PowerShell / Git Bash
- Markdown

## 📂 Project Structure

```text
cynaris-week-1-day-5/
├── index.html
├── script.js
├── .gitignore
└── README.md
```

## 🚀 Git Workflow

### 1. Initialize the repository

```bash
git init
git branch -M main
git add .
git commit -m "chore: initial commit"
```

### 2. Create a feature branch

```bash
git switch -c feature/week-1-day-5
```

### 3. Stage and commit changes

```bash
git add .
git commit -m "feat: git-workflow week-1-day-5 complete"
```

### 4. Push the feature branch

```bash
git push -u origin feature/week-1-day-5
```

### 5. Create a Pull Request

Open a pull request on GitHub using:

- **Base branch:** `main`
- **Compare branch:** `feature/week-1-day-5`

Review the changes and merge the pull request when everything is ready.

## 🌿 Important Git Commands

| Command | Purpose |
|---|---|
| `git status` | Check the working tree |
| `git branch` | List branches |
| `git switch -c branch-name` | Create and switch to a branch |
| `git add .` | Stage changes |
| `git commit -m "message"` | Commit staged changes |
| `git log --oneline` | View commit history |
| `git merge branch-name` | Merge another branch |
| `git rebase -i HEAD~3` | Interactively edit recent commits |
| `git push` | Push commits to a remote repository |
| `git pull` | Fetch and integrate remote changes |

## 🔀 Merge vs Rebase

- **Merge:** Combines changes from different branches and generally preserves the branching history.
- **Rebase:** Replays commits on top of another base commit to create a more linear history.

Avoid rebasing shared commits unless the team has agreed to rewrite the history.

## ⚔️ Merge Conflict Resolution

1. Identify the conflicted files using `git status`.
2. Open each conflicted file.
3. Review the conflict markers.
4. Choose or combine the correct changes.
5. Remove all conflict markers.
6. Test the updated code.
7. Stage and commit the resolution.

## 🚫 .gitignore

A `.gitignore` file prevents unnecessary or sensitive files from being tracked.

Example:

```gitignore
node_modules/
.env
.env.local
dist/
build/
coverage/
npm-debug.log*
.DS_Store
```

Never commit passwords, API keys, or other secrets.

## ✅ Learning Outcomes

- Practised Git branching and commits.
- Learned how to create a pull request.
- Understood interactive rebase and commit squashing.
- Learned the purpose of `.gitignore`.
- Studied merge conflict resolution.
- Improved understanding of collaborative development workflows.

## 📎 Deliverables

- GitHub Repository: [Add your repository URL]
- Pull Request: [Add your pull request URL]

## 📚 Learning Resources

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Documentation](https://docs.github.com/)
- [GitHub Flow](https://docs.github.com/en/get-started/using-github/github-flow)

---

**Learning Path:** Cynaris Learning  
**Week:** 1  
**Day:** 5  
**Topic:** Git & GitHub for Web Developers
