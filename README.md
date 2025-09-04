
# Arun Vangala – Full Stack Engineer

# Learn Git & GitHub

Welcome to the **Learn Git & GitHub** repository!  
This repository is a **complete guide** for beginners and intermediate users to learn Git and GitHub with **real-time examples, workflows, and best practices**.

---

## 📌 What is Git?

- Git is a **distributed version control system** that tracks changes in code files.  
- It allows developers to **collaborate**, **rollback changes**, and manage **multiple branches**.  
- Works **locally on your machine**, no internet required to use Git.

---

## 📌 What is GitHub?

- GitHub is a **cloud-based hosting service for Git repositories**.  
- It allows **team collaboration**, **pull requests**, **issue tracking**, and **CI/CD integration**.  
- Think of GitHub as the **online home** for your Git projects.

---

## 📝 Key Uses of Git & GitHub

- Version control for code  
- Collaboration on projects with multiple developers  
- Branching and merging for feature development  
- Storing code securely on the cloud  
- Reviewing code through Pull Requests  
- Maintaining a history of all project changes  

---

## 💻 Git Workflow (End-to-End)

1. **Working Directory** – files you edit.  
2. **Staging Area** – files prepared to commit.  
3. **Local Repository** – commits stored locally.  
4. **Remote Repository (GitHub)** – shared code online.



Working Directory → Staging → Local Repo → Remote Repo


---

## ⚡ Basic Git Commands

```bash
git init                   # Initialize repository
git clone <repo_url>       # Clone repo
git status                 # Check current status
git add <file>             # Stage file
git add .                  # Stage all changes
git commit -m "message"    # Commit changes
git push origin main       # Push to GitHub
git pull origin main       # Pull latest changes

🌿 Branching & Merging
git branch                  # List branches
git branch <branch_name>    # Create new branch
git checkout <branch_name>  # Switch branch
git checkout -b <branch_name>  # Create & switch
git merge <branch_name>     # Merge into current branch
git branch -d <branch_name>  # Delete branch

🔄 Undo & Reset
git log                    # Show commit history
git diff                   # Show changes
git reset <file>           # Unstage file
git checkout -- <file>     # Discard changes
git reset --hard HEAD~1    # Reset last commit
git revert <commit_id>     # Undo commit safely

📂 Real-Time Workflow Examples
1. Solo Developer
git init
git add .
git commit -m "Initial commit"
git remote add origin <url>
git push -u origin main
# Work & push directly to main

2. Small Team (Feature Branch)
git checkout -b feature/login
# Make changes
git add .
git commit -m "Added login"
git push -u origin feature/login
# Open Pull Request on GitHub

3. Large Team (Fork & Pull Request)
git clone <forked_repo>
git remote add upstream <original_repo>
git fetch upstream
git checkout main
git merge upstream/main
git checkout -b feature/payment
# Work & push to fork
# Open Pull Request from fork → original repo

4. Hotfix Workflow
git checkout main
git pull origin main
git checkout -b hotfix/critical-bug
# Fix bug
git commit -am "Fixed critical bug"
git push origin hotfix/critical-bug
# Open PR → Merge → Deploy

📑 Best Practices

Commit often with clear messages

Always pull before pushing

Use .gitignore for unnecessary files

Use branches for new features

Review code before merging

Keep main branch stable

📦 Optional Files in Repo

git-commands.txt → Text file with key Git commands

Git_GitHub_Commands_Guide.pdf → Full guide PDF

git-commands-cheatsheet.txt → Expanded commands with workflows

🚀 How to Use This Repository

Clone the repo

git clone https://github.com/<your-username>/learn-git-github.git


Open in VS Code

cd learn-git-github
code .


Check commands

Open git-commands.txt or git-commands-cheatsheet.txt

Follow commands step-by-step

Practice workflows with branches, commits, merges, and pull requests.
