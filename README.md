# git Assignment

Steps in this readme file are a sample for this project and not of the actual code. You can add your own files and try the commands.

## project link

- ([repo link](https://github.com/sravanTIRU/git-assignment))

## Overview

This project demonstrates the fundamental concepts of Git and GitHub, including repository setup, branch management, commits, pull requests, and merging code.

## Objectives

- Set up a GitHub account and create a repository.
- Configure SSH keys for authentication.
- Clone the repository and push code.
- Manage branches (`development`, `staging`, `main`).
- Work with feature branches, commit changes, and merge them.
- Create pull requests (PRs) and merge code via PRs.
- Understand the working directory, local repository, and remote repository.

## Prerequisites

- Installed Git ([Download Git](https://git-scm.com/downloads))
- GitHub account ([Sign Up](https://github.com/))
- SSH key configured for GitHub

## Setup Instructions

### 1. Clone the Repository

```bash
git clone git@github.com:your-username/git-assignment.git
cd git-assignment
```

### 2. Create a Feature Branch

```bash
git checkout -b feature-branch
```

### 3. Make Changes and Commit

```bash
echo "print('Hello GitHub')" > app.py
git add app.py
git commit -m "Added app.py with a sample print statement"
```

### 4. Push Changes and Create a PR

```bash
git push origin feature-branch
```

- Go to GitHub and open a pull request to merge `feature-branch` into `main`.
- Review and merge the PR.

### 5. Merge Changes Locally

```bash
git checkout main
git pull origin main
```

## Understanding Git Workflow

- **Working Directory**: Local project files in their current state.
- **Local Repository**: Git-tracked changes and commits on your machine.
- **Remote Repository**: Hosted on GitHub, contains pushed commits.

## Author

[sravan teja]
