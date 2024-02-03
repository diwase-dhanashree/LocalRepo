# Git Repository with Feature Branch

Welcome to the Git Repository with Feature Branch! This project demonstrates the basic Git workflow, including creating a local repository, pushing it to a remote repository on GitHub, and managing branches.

## Project Overview

- **Local Repository:**
  - The project starts with the creation of a local Git repository on your machine.

- **Remote Repository:**
  - The local repository is then pushed to a remote repository on GitHub.

- **Branches:**
  - Two branches are created:
    - **Main Branch:** The default branch for the project.
    - **Feature1 Branch:** A feature branch where additional changes or features are developed.

- **Pull Requests:**
  - Changes made in the Feature1 branch are merged into the Main branch using pull requests.

## Folder Structure


## Git Commands

### Clone the Repository:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```
Create and Switch to a New Branch: git checkout -b feature1

Make Changes and Commit: 
- Make changes to files
- git add .
- git commit -m "Add new feature in feature1 branch"
  
Switch to the Main Branch:
- git checkout main
  
Merge Feature1 Branch into Main:
- git merge feature1

Push Changes to GitHub:
- git push origin main
