# 🚀 Complete Git Learning Path - Hands-On Tasks

Welcome to the **Complete Git Learning Path** – a hands-on journey through the world of Git! Whether you're a beginner or brushing up on advanced concepts, this repo will walk you through real-world scenarios step-by-step.

---

## 📚 Overview

This repository provides a structured, phase-wise learning experience to master Git and GitHub. Each task builds on the previous one, combining commands, workflows, and best practices.

> 🧠 *Learn by doing: each phase includes actionable tasks, goals, and commands you’ll use in real-world development.*

---

## 🧩 Phase 1: Git Fundamentals

### 🛠️ Task 1: Setup and First Repository
**Goal:** Configure Git and create your first local repository.

**Actions:**
- Install Git and configure your identity
- Create a `git-practice` directory
- Initialize a Git repository
- Create and commit a `README.md` file
- Check status and commit log

**Key Commands:**  
`git config`, `git init`, `git add`, `git commit`, `git status`, `git log`

---

### 📄 Task 2: Basic File Operations
**Goal:** Understand Git's workflow with multiple files.

**Actions:**
- Create `index.html`, `style.css`, `script.js`
- Stage files separately and together
- Make individual commits
- Use diff to inspect changes

**Key Commands:**  
`git add`, `git diff`, `git diff --staged`

---

### 🚫 Task 3: Git Ignore and File Management
**Goal:** Learn to exclude files and manage deletions/renames.

**Actions:**
- Add `.gitignore`
- Rename and delete files
- Recover deleted files from history

**Key Commands:**  
`git mv`, `git rm`, `git checkout -- <file>`

---

## 🌿 Phase 2: Branching and Merging

### 🌱 Task 4: Your First Branch
**Goal:** Create and switch branches.

**Actions:**
- Create `feature-navbar` branch
- Make and commit changes
- Switch between branches and compare

**Key Commands:**  
`git branch`, `git checkout`, `git checkout -b`

---

### 🔀 Task 5: Merging Branches
**Goal:** Merge feature branches into main.

**Actions:**
- Create `feature-footer`
- Merge into main branch
- Delete merged branches
- View commit graph

**Key Commands:**  
`git merge`, `git branch -d`, `git log --graph --oneline`

---

### ⚔️ Task 6: Handling Merge Conflicts
**Goal:** Understand and resolve merge conflicts.

**Actions:**
- Create conflicting branches
- Merge with conflict
- Manually resolve and complete merge

**Key Commands:**  
`git merge`, `git add`, `git commit`

---

## 🌐 Phase 3: Working with Remote Repositories

### ☁️ Task 7: GitHub Integration
**Goal:** Push and pull from GitHub.

**Actions:**
- Connect to GitHub
- Push/pull code
- Handle conflicts between local and remote

**Key Commands:**  
`git remote add`, `git push`, `git pull`, `git fetch`

---

### 🍴 Task 8: Cloning and Forking Workflow
**Goal:** Collaborate using forks and pull requests.

**Actions:**
- Fork and clone repos
- Push changes
- Open a pull request

**Key Commands:**  
`git clone`, `git remote add upstream`, `git push origin`

---

### 👥 Task 9: Collaboration Simulation
**Goal:** Simulate real-world collaboration scenarios.

**Actions:**
- Clone the repo twice
- Push conflicting changes
- Learn to rebase and sync before pushing

**Key Commands:**  
`git fetch`, `git pull --rebase`, `git push --force-with-lease`

---

## 🔧 Phase 4: Advanced Git Operations

### 🔄 Task 10: Rebasing Fundamentals
**Goal:** Practice interactive rebase.

**Actions:**
- Squash, split, and reorder commits
- Rebase vs merge comparison

**Key Commands:**  
`git rebase -i`, `git commit --amend`, `git rebase main`

---

### 🧳 Task 11: Stashing and Temporary Work
**Goal:** Save and restore work in progress.

**Actions:**
- Use stash during urgent tasks
- Pop/apply stash later
- Handle stash conflicts

**Key Commands:**  
`git stash`, `git stash pop`, `git stash list`

---

### 🍒 Task 12: Cherry-Picking and Selective Merging
**Goal:** Pick specific commits across branches.

**Actions:**
- Cherry-pick single and multiple commits
- Use for hotfixes and specific merges

**Key Commands:**  
`git cherry-pick`, `git cherry-pick <range>`

---

## 🕵️ Phase 5: Git History and Debugging

### 🔍 Task 13: Exploring History
**Goal:** Search and navigate Git history.

**Actions:**
- Use grep and search filters
- Use blame and bisect

**Key Commands:**  
`git log`, `git bisect`, `git blame`, `git log --follow`

---

### 🛑 Task 14: Undoing Changes (The Safety Net)
**Goal:** Learn to safely undo changes.

**Actions:**
- Unstage and discard changes
- Revert and reset commits
- Recover lost work with reflog

**Key Commands:**  
`git reset`, `git revert`, `git reflog`, `git fsck`

---

### 🧬 Task 15: Advanced Undoing Scenarios
**Goal:** Handle complex undo tasks.

**Actions:**
- Undo merge commits
- Recover deleted branches
- Push corrected histories

**Key Commands:**  
`git revert -m`, `git push --force-with-lease`, `git reflog`

---

## 🔁 Phase 6: Git Workflows and Best Practices

### 🌊 Task 16: Git Flow Workflow
**Goal:** Use the Git Flow branching model.

**Actions:**
- Create feature, release, and hotfix branches
- Practice full Git Flow cycle

**Key Commands:**  
Git Flow CLI or manual branch management

---

### 🔄 Task 17: GitHub Flow Simulation
**Goal:** Practice the GitHub Flow model.

**Actions:**
- Feature branches, PRs, and branch protection
- Implement CI/CD workflow

**Key Commands:**  
GitHub CLI / web UI

---

### 🧱 Task 18: Monorepo and Submodules
**Goal:** Manage complex projects with submodules.

**Actions:**
- Add, update, and sync submodules
- Resolve submodule conflicts

**Key Commands:**  
`git submodule add`, `git submodule update`, `git submodule foreach`

---

## ⚙️ Phase 7: Advanced Topics and Edge Cases

### 🪝 Task 19: Hooks and Automation
**Goal:** Use Git hooks for automation.

**Actions:**
- Add `pre-commit`, `commit-msg`, and `post-receive` hooks

**Key Commands:**  
Git hook scripts, `git commit --no-verify`

---

### 🗃️ Task 20: Performance and Large Files
**Goal:** Handle large repositories efficiently.

**Actions:**
- Use Git LFS
- Shallow clone and sparse-checkout

**Key Commands:**  
`git lfs`, `git clone --depth`, `git sparse-checkout`

---

### ⚔️ Task 21: Advanced Conflict Resolution
**Goal:** Master difficult merge scenarios.

**Actions:**
- Use mergetools
- Resolve binary and rename conflicts

**Key Commands:**  
`git mergetool`, `git merge -X`, `git rebase --strategy`

---

### 🧠 Task 22: Git Internals and Troubleshooting
**Goal:** Understand and inspect Git internals.

**Actions:**
- Explore `.git` structure
- View blobs, commits, trees
- Fix corruption and recover

**Key Commands:**  
`git cat-file`, `git ls-tree`, `git fsck`, `git gc`

---

## 📦 Phase 8: Real-World Scenarios

### 🔍 Task 23: Code Review Workflow
**Goal:** Implement a complete review process.

**Actions:**
- Draft PRs, assign reviewers, squash after approval

---

### 🚀 Task 24: Release Management
**Goal:** Versioning and tagging releases.

**Actions:**
- Create semantic tags
- Generate changelogs
- Backport fixes

**Key Commands:**  
`git tag`, `git describe`, `git show-branch`

---

### 🧯 Task 25: Disaster Recovery
**Goal:** Handle worst-case scenarios.

**Actions:**
- Recover deleted data and broken merges
- Migrate from another VCS

**Key Commands:**  
`git reflog`, `git fsck`, migration tools

---

Happy committing! 💥  
*Contributions, suggestions, and improvements are always welcome.*

```

