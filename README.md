# 🌱 Git Learning Project

> 🚀 *A step-by-step journey through the Git workflow — from initialization to pushing changes to GitHub.*

---

## 🧭 Overview

This repository demonstrates my understanding of **Git basics** — including repository creation, file tracking, committing changes, and configuring Git globally.  
It serves as a hands-on exercise in version control and GitHub collaboration 💻.

---

## 📂 Project Steps

Below is the complete sequence of Git commands used in this exercise:

### 1️⃣ Setting up the project
```bash
mkdir learn_git
cd learn_git
```

### 2️⃣ Creating files
```bash
echo "This is my third file" > third.txt
```

### 3️⃣ Initialize Git repository
```bash
git init
```

### 4️⃣ Stage and commit the first file
```bash
git add third.txt
git commit -m "adding third.txt"
```

### 5️⃣ Check commit log
```bash
git log
```

### 6️⃣ Add another file and commit
```bash
echo "This is my fourth file" > fourth.txt
git add fourth.txt
git commit -m "adding fourth.txt"
```

### 7️⃣ Remove a file and commit
```bash
rm third.txt
git add .
git commit -m "removing third.txt"
```

### 8️⃣ View commit history
```bash
git log
```

### 9️⃣ Change Git global configuration
```bash
git config --global core.pager cat
```

### 🔟 View all global Git settings
```bash
git config --global --list
```

### 11️⃣ Connect and push to GitHub
```bash
git remote add origin https://github.com/ivankihoria805-prog/learn_git.git
git branch -M main
git push -u origin main
```

---

## 🧾 Git Command Summary Table

| **Step** | **Command** | **Description** |
|-----------|--------------|-----------------|
| 1️⃣ | `mkdir learn_git` | Creates a new folder named *learn_git*. |
| 2️⃣ | `cd learn_git` | Moves into the *learn_git* directory. |
| 3️⃣ | `git init` | Initializes a new Git repository. |
| 4️⃣ | `git add third.txt` | Stages the file *third.txt* for commit. |
| 5️⃣ | `git commit -m "adding third.txt"` | Commits the staged file with a message. |
| 6️⃣ | `git log` | Displays commit history. |
| 7️⃣ | `echo "This is my fourth file" > fourth.txt` | Creates *fourth.txt* with sample content. |
| 8️⃣ | `git add fourth.txt` | Stages the new file for commit. |
| 9️⃣ | `git commit -m "adding fourth.txt"` | Commits the new file. |
| 🔟 | `rm third.txt` | Deletes *third.txt*. |
| 11️⃣ | `git add .` | Stages all changes (including deletions). |
| 12️⃣ | `git commit -m "removing third.txt"` | Commits the deletion. |
| 13️⃣ | `git config --global core.pager cat` | Changes Git pager setting for better log readability. |
| 14️⃣ | `git config --global --list` | Lists all global Git configuration settings. |
| 15️⃣ | `git push -u origin main` | Pushes commits to GitHub. |

---

## 🖼️ Screenshots Included
1. Folder creation (`mkdir`)
2. Git initialization (`git init`)
3. Staging files (`git add`)
4. Each commit (`git commit`)
5. Commit logs (`git log`)
6. Global settings (`git config --global --list`)
7. Successful GitHub push

---

## ✅ Summary

This exercise helped demonstrate:
- The **Git workflow** (init → add → commit → log → push)
- **File tracking** and version control
- **Global configuration** setup
- How to **connect a local repo to GitHub**

---

**Author:** *Ivan Kihoria*  
**GitHub:** [@ivankihoria805-prog](https://github.com/ivankihoria805-prog)  
**Repository:** [https://github.com/ivankihoria805-prog/learn_git](https://github.com/ivankihoria805-prog/learn_git)  
**Date:** *October 27, 2025* 

---

## 💡 Learning Reflection

> Through this project, I strengthened my understanding of how Git tracks changes, manages version history, and facilitates teamwork via GitHub.  
> Each commit tells a story of progress 📈 and builds confidence in version control.

---

### ✨ Final Thoughts

> “Code is temporary, but commits are forever.”  
> Keep learning, keep committing, and keep growing 🌿

---

