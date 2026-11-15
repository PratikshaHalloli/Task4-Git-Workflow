
# Task 4: Version-Controlled DevOps Project Using Git

## Project Overview

This project demonstrates how Git and GitHub are used to manage a DevOps project through version control. It follows Git best practices, including repository initialization, branching, commits, pull requests, merging, and version tagging.

## Objectives

- Understand and implement Git version control.
- Create and manage Git branches.
- Track project changes using meaningful commits.
- Use GitHub for remote repository management.
- Practice Pull Request and merge workflows.
- Maintain project documentation using Markdown.
- Use `.gitignore` to exclude unnecessary files.

## Tools and Technologies

- Git – Distributed version control system.
- GitHub – Remote repository hosting and collaboration.
- Kali Linux – Development environment.
- Vim – Text editor.
- Markdown – Project documentation.
- Bash – Shell scripting.

## Project Structure

```text
Task4-Git-Workflow/
├── README.md
├── .gitignore
├── docs/
│   ├── development.md
│   ├── GIT_WORKFLOW.md
│   └── feature.md
└── scripts/
    └── hello.sh
```

## Git Branching Strategy

This project uses three main branches:

- `main` – Contains the stable project version.
- `dev` – Used for development and integration.
- `feature/add-project-info` – Used to develop individual features.

## Git Workflow

1. Initialize the local Git repository.
2. Add project files and create the initial commit.
3. Connect the local repository to GitHub.
4. Create and work on the `dev` branch.
5. Create a feature branch for new changes.
6. Push branches to GitHub.
7. Create Pull Requests to merge feature into dev and dev into main.
8. Create a version tag for the release.

## Important Git Commands

```bash
git init -b main
git add .
git commit -m "Initial commit"
git branch
git checkout -b dev
git checkout -b feature/add-project-info
git remote add origin <repository-url>
git push -u origin main
git merge
git tag -a v1.0 -m "First release"
```

## Version Tagging

The project uses an annotated Git tag named `v1.0` to identify the first project release.

## Learning Outcomes

- Understanding Git and GitHub.
- Managing branches and commits.
- Working with Pull Requests.
- Understanding merge conflicts and their resolution.
- Using `.gitignore` and Git tags.
- Maintaining structured project documentation.

## Conclusion

This project demonstrates a basic Git-based DevOps workflow and the importance of version control, collaboration, and organized project management.

