Practical Title:
To understand version control concepts and perform basic source code management using Git

Name:
Parambrata Sanyal

Date:
March 31, 2026

Theory:

1. What is Version Control System (VCS)?
A Version Control System (VCS) is a software tool that records changes made to files over time. It helps track history, compare versions, recover older versions, and support collaboration among multiple developers.

2. Types of Version Control Systems (Centralized vs Distributed)
Centralized VCS (CVCS):
- A single central server stores all version history.
- Developers check out files from the central server.
- Internet/server dependency is high.
- Example: SVN.

Distributed VCS (DVCS):
- Every developer has a full local copy of the repository and history.
- Most operations are fast and can be done offline.
- Better flexibility for branching and merging.
- Example: Git.

3. What is Git?
Git is a distributed version control system used to track source code changes, support team collaboration, and manage project history efficiently through commits, branches, merges, and remote repositories.

4. Key Git Terminologies
Repository:
A folder tracked by Git that stores files and complete version history.

Commit:
A saved snapshot of changes in the repository with a message.

Branch:
An independent line of development used to work on features/fixes without affecting the main code.

Merge:
The process of combining changes from one branch into another branch.

Clone:
Creating a local copy of an existing remote repository.

Procedure:

Step 1: Install Git and verify installation
Command:
    git --version

Verified output:
    git version 2.53.0.windows.2

Step 2: Configure Git
Commands:
    git config user.name "Parambrata Sanyal"
    git config user.email "sparambrata@users.noreply.github.com"

Verification commands:
    git config user.name
    git config user.email

Verified output:
    Parambrata Sanyal
    sparambrata@users.noreply.github.com

Step 3: Create a Repository
Command:
    git init

Note:
Repository already existed in this workspace and was used for this practical.

Step 4: Create a file and add content
File created:
    Git_Practical_1.md

Step 5: Add and Commit
Commands:
    git add Git_Practical_1.md
    git commit -m "Add Git practical report"

Step 6: Connect to GitHub and Push
Commands:
    git remote -v
    git switch -c main
    git push -u origin main

Verified remote:
    https://github.com/sparambrata/Devops-Class.git

Step 7: Pull changes
Command:
    git pull origin main

Verified output:
    Already up to date.

Output Screenshots (Paste screenshots of each step):

Picture 1: Git version verification
Capture terminal after running:
    git --version

Picture 2: Git configuration
Capture terminal after running:
    git config user.name
    git config user.email

Picture 3: Repository status or initialization
Capture terminal after running:
    git status -sb

Picture 4: File creation
Capture editor showing Git_Practical_1.md file content.

Picture 5: Add and commit
Capture terminal after running:
    git add Git_Practical_1.md
    git commit -m "Add Git practical report"

Picture 6: Push to GitHub
Capture terminal after running:
    git push -u origin main

Picture 7: Pull changes
Capture terminal after running:
    git pull origin main

Picture 8: Branch creation and merge
Capture terminal after running Task 2 commands.

Activity / Task:

Task 1:
Create your own GitHub repository and push at least one file.

Repository Link:
https://github.com/sparambrata/Devops-Class

Additional useful links:
Main branch:
https://github.com/sparambrata/Devops-Class/tree/main

Latest practical file:
https://github.com/sparambrata/Devops-Class/blob/main/Git_Practical_1.md

Task 2:
Create a new branch and merge it with main branch.

Commands Used:
    git switch -c practical-branch
    git add Git_Practical_1.md
    git commit -m "Update report from practical branch"
    git switch main
    git merge practical-branch --no-ff -m "Merge practical-branch into main"
    git push

Proof links for branch and merge commits:
Branch commit:
https://github.com/sparambrata/Devops-Class/commit/55628b5

Merge commit:
https://github.com/sparambrata/Devops-Class/commit/fa15501

Latest report update:
https://github.com/sparambrata/Devops-Class/commit/4095391

Advantages of Git:
1. Fast local operations and efficient performance.
2. Strong branching and merging workflow.
3. Distributed model supports offline work.
4. Reliable commit history and rollback support.
5. Excellent collaboration via GitHub integration.

Challenges in Version Control:
1. Merge conflicts can be difficult to resolve.
2. Poor branch strategy can make history confusing.
3. Wrong staging or commit practices can push unwanted files.
