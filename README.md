# A02

Author: Xavier Stroman
Course: IS117
Date: September 2026

Introduction

This tutorial will walk you through setting up Git, WebStorm, and GitHub from scratch. By the end, you will be able to create a repository, make commits, push code, and collaborate using version control.

PART 1: Directions on Using WebStorm with Git and GitHub
Step 1: Create a GitHub Account
Go to https://github.com
Click Sign Up in the top right corner
Enter your email address, create a password, and choose a username
Verify your email address
You now have a GitHub account

Step 2: Download and Install Git
Go to https://git-scm.com/downloads
Select your operating system (Windows, Mac, or Linux)
Download and run the installer
Follow the default installation settings and click Next through each screen
Once installed, open your terminal or command prompt and type:
   git --version

If a version number appears, Git is successfully installed.

Step 3: Download and Install WebStorm
Go to https://www.jetbrains.com/webstorm/download/
Select your operating system and click Download
Run the installer and follow the on-screen prompts
Launch WebStorm once installation is complete
You can apply for a free student license at https://www.jetbrains.com/community/education/ using your school email

Step 4: Configure Git in WebStorm
Open WebStorm
Go to File → Settings (Windows) or WebStorm → Preferences (Mac)
Navigate to Version Control → Git
Make sure the path to your Git executable is filled in (WebStorm usually detects it automatically)
Click Test to confirm Git is working, then click OK

Step 5: Connect WebStorm to GitHub
In WebStorm, go to File → Settings → Version Control → GitHub
Click the + button to add an account
Select Log In via GitHub
A browser window will open — log in to your GitHub account and authorize JetBrains
Once authorized, your GitHub account will appear in WebStorm

Step 6: Create a New Repository on GitHub
Log in to https://github.com
Click the + icon in the top right corner and select New repository
Name your repository (e.g., A02)
Add a description (optional)
Set it to Public
Check the box that says Add a README file
Click Create repository

Step 7: Clone the Repository into WebStorm
On your GitHub repository page, click the green Code button
Copy the HTTPS URL (e.g., https://github.com/yourUsername/A02.git)
Open WebStorm
Go to File → New → Project from Version Control
Paste the repository URL into the URL field
Choose a local directory to save the project
Click Clone
The repository is now on your computer and open in WebStorm

Step 8: Make Changes and Commit
In WebStorm, open the README.md file (or any file you want to edit)
Make your changes
When ready to save your progress, go to Git → Commit (or press Ctrl+K / Cmd+K)
Write a clear commit message describing what you changed (e.g., Feature: added glossary definitions)
Click Commit to save locally, or Commit and Push to save and upload to GitHub

Step 9: Push Changes to GitHub
If you only committed (not pushed), go to Git → Push (or press Ctrl+Shift+K / Cmd+Shift+K)
WebStorm will show you what commits will be pushed
Click Push
Your changes are now live on GitHub

Step 10: Pull Updates from GitHub
If someone else made changes to the repository (or you made changes on another computer), you need to pull the latest version
Go to Git → Pull
WebStorm will download and merge the latest changes into your local copy

Step 11: Create and Merge a Branch
To create a new branch, go to Git → Branches → New Branch
Name your branch (e.g., feature-update) and click Create
Make changes and commit them on this branch
When ready, go to Git → Merge and select the branch you want to merge into main
Resolve any merge conflicts if they appear by choosing which version of the code to keep
Push the merged changes to GitHub

PART 2: Glossary
Branch — A separate version of the repository that allows you to work on changes without affecting the main codebase. Branches let multiple people work in parallel.
Clone — The process of copying a remote repository from GitHub onto your local computer so you can work on it.
Commit — A saved snapshot of changes in your local repository. Each commit should have a clear message describing what was changed.
Fetch — A command that downloads changes from a remote repository without automatically merging them into your current branch.
GIT — A free, open-source distributed version control system that tracks changes in files and coordinates work among multiple people.
Github — A cloud-based platform that hosts Git repositories and provides collaboration tools like pull requests, issues, and project boards.
Merge — The process of combining changes from one branch into another. Git attempts to automatically integrate the changes.
Merge Conflict — An error that occurs when two branches have made conflicting changes to the same part of a file and Git cannot automatically resolve which version to keep.
Push — The process of uploading your local commits to a remote repository on GitHub so others can access your changes.
Pull — The process of fetching and automatically merging changes from a remote repository into your local branch.
Remote — A version of your repository that is hosted on a server (like GitHub) rather than on your local machine. You push to and pull from remotes.
Repository — A storage location for a project that contains all of the project's files and the entire history of changes made to them.

References:
Github.com 
www.jetbrains.com/webstorm
