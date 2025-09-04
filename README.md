# Learn Git & GitHub

This repository contains a complete guide and commands for Git and GitHub.

## Files
- `git-commands.txt`: Cheatsheet of Git commands with examples.

## How to Use
1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/learn-git-github.git


Open git-commands.txt to see all commands.

Follow best practices for committing, branching, and pushing.

Add, commit, and push:

git add README.md
git commit -m "Added README file"
git push origin main

4. Create Branches for Updates

Instead of updating main directly, create branches for new content or experiments:

git checkout -b new-commands
# make changes
git add .
git commit -m "Added advanced Git commands"
git push -u origin new-commands


Then you can create a Pull Request on GitHub to merge it into main.

5. Optional: Add PDF/Document

If you have the PDF guide we created, you can add it here too:

git add Git_GitHub_Commands_Guide.pdf
git commit -m "Added PDF guide"
git push origin main