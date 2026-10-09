
# DevOps Git Workflow Project

## Overview

This project demonstrates Git and GitHub version control best practices used in DevOps workflows.

## Objectives

* Practice Git initialization and repository management.
* Implement main, dev, and feature branches.
* Use pull requests for controlled merging.
* Maintain meaningful commit messages.
* Apply .gitignore rules and version tags.
* Document project activities using Markdown.

## Tools

* Git
* GitHub
* Markdown
* Bash

## Branching Strategy

* `main`: stable, reviewed code.
* `dev`: integration and testing.
* `feature/*`: isolated development tasks.

## Workflow

1. Create a feature branch from dev.
2. Implement and test the changes.
3. Commit with a descriptive message.
4. Push the feature branch to GitHub.
5. Open a pull request into dev.
6. Review and merge the pull request.
7. Test the integrated changes.
8. Open a pull request from dev into main.
9. Merge and create a version tag.

## Project Structure

```text
devops-git-workflow/
├── README.md
├── .gitignore
├── docs/
│   └── git-workflow.md
└── scripts/
    └── hello.sh
```

## Version

Initial release: v1.0.0

## Learning Outcomes

Understanding of Git branching, commits, remote repositories, pull requests, merge conflict resolution, tags, and documentation.

