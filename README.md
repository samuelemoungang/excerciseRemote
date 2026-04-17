# excerciseRemote

A hands-on Git practice repository created as part of coursework at **HES-SO Valais-Wallis** (November 2025). The goal was to learn and apply core Git and GitHub workflows by doing — not just reading about them.

---

## 🎯 What this repo covers

This repository was used to practice the following Git concepts:

| Concept | How it was practised |
|---|---|
| `git init` / `git clone` | Initializing a local repo and cloning from GitHub |
| `git add` / `git commit` | Staging and committing changes with meaningful messages |
| `git push` / `git pull` | Syncing local and remote repositories |
| **Branches** | Creating a `new-feature` branch, working on it independently |
| **Merging** | Merging `new-feature` back into `main` |
| **Binary files** | Tracking a `.docx` file to understand how Git handles non-text content |
| `.gitignore` | Configuring which files Git should ignore |
| **Scavenger hunt** | Exploring the repo's history and structure as a guided exercise |

---

## 📜 Commit history

```
d068436  first commit                         ← README added
393cf0d  Merge branch 'new-feature'           ← merge from feature branch
d3c0bd0  Adding a file_test.txt               ← committed on new-feature branch
acb4ca6  Modified                             ← update to git-scavenger-hunt
2cf5327  new file: hello.txt                  ← simple text file added
58e2891  Adding og .gitignore                 ← .gitignore + library files updated
ee3e48b  Exercise: Binary Files               ← library.docx first added
4a707e1  test file                            ← library.txt first added
```

---

## 📁 Repository contents

```
excerciseRemote/
├── .gitignore             # Patterns for ignored files
├── README.md              # This file
├── hello.txt              # Simple text file ("Hello there!")
├── file_test.txt          # Empty file added via the new-feature branch
├── library.txt            # Contains git init and git stash help output
├── library.docx           # Binary file — same content as library.txt
└── git-scavenger-hunt/    # Directory used for the scavenger hunt exercise
```

---

## 🌿 Branch workflow practiced

```
main
 ├── 4a707e1  test file
 ├── ee3e48b  Exercise: Binary Files
 ├── 58e2891  Adding og .gitignore
 ├── 2cf5327  new file: hello.txt
 │
 └── new-feature (merged)
      └── d3c0bd0  Adding a file_test.txt
           └── 393cf0d  Merge branch 'new-feature' ← back into main
```

---

## 🔑 Key commands used

```bash
# Initialize and connect
git init
git remote add origin <url>

# Stage and commit
git add .
git commit -m "your message"

# Push and pull
git push origin main
git pull origin main

# Branching and merging
git checkout -b new-feature
git checkout main
git merge new-feature

# Inspect history
git log --oneline --all
git log --graph --oneline --all
```

---

## 📚 Context

- **Course**: Introduction to Git / Software Engineering tools
- **Institution**: HES-SO Valais-Wallis
- **Date**: November 2025
- **Author**: [@samuelemoungang](https://github.com/samuelemoungang)
