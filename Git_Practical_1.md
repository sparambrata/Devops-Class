Practical Title:
To understand version control concepts and perform basic source code management using Git

Date:
March 31, 2026

Theory

1. What is Version Control System (VCS)?
A Version Control System is a tool that tracks changes in source code and files over time. It allows multiple people to collaborate, keeps history of changes, and helps restore previous versions when needed.

2. Types of Version Control Systems (Centralized vs Distributed)
- Centralized VCS:
  A single central server stores the repository, and users check out files from that server.
  Example: SVN (Subversion).
- Distributed VCS:
  Every developer has a full copy of the repository, including complete history.
  Example: Git.

3. What is Git?
Git is a distributed version control system designed for speed, reliability, and collaborative software development. It enables branching, merging, and tracking file history efficiently.

4. Key Git Terminologies
- Repository:
  A storage location containing project files and their version history.
- Commit:
  A snapshot of staged changes saved to repository history with a message.
- Branch:
  An independent line of development in a repository.
- Merge:
  Combining changes from one branch into another branch.
- Clone:
  Creating a local copy of an existing remote repository.

Procedure

Step 1: Install Git and verify installation
Command used:
git --version

Output Screenshot:
[Insert Screenshot - Git version output]

Step 2: Configure Git
Commands used:
git config --global user.name "Parambrata Sanyal"
git config --global user.email "sparambrata@users.noreply.github.com"

Output Screenshot:
[Insert Screenshot - Git config values]

Step 3: Create a Repository
Command used (already created repository in workspace):
git init

Output Screenshot:
[Insert Screenshot - Repository initialization/status]

Step 4: Create a file and add content
File created:
Git_Practical_1.md

Output Screenshot:
[Insert Screenshot - File creation]

Step 5: Add and Commit
Commands used:
git add Git_Practical_1.md
git commit -m "Add Git practical report"

Output Screenshot:
[Insert Screenshot - Commit output]

Step 6: Connect to GitHub and Push
Commands used:
git remote -v
git push -u origin main

Output Screenshot:
[Insert Screenshot - Push output]

Step 7: Pull changes
Command used:
git pull origin main

Output Screenshot:
[Insert Screenshot - Pull output]

Activity / Task

Task 1:
Create your own GitHub repository and push at least one file.

Repository Link:
https://github.com/sparambrata/Devops-Class

Task 2:
Create a new branch and merge it with main branch.

Commands Used:
(To be updated after branch and merge operations)

Advantages of Git:
1. Fast and efficient version tracking.
2. Strong branching and merging support.
3. Distributed workflow enables offline work.
4. Easy collaboration through platforms like GitHub.
5. Reliable history and rollback capability.

Challenges in Version Control:
1. Merge conflicts can be difficult for beginners.
2. Incorrect branching strategy can create confusion.
3. Misconfigured ignore/staging may commit unwanted files.
Branch Activity Note:
Created branch practical-branch, updated report, and prepared for merge into main.

