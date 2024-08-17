# automating-github-tasks

# Git Automation Script

## Overview

This Bash script automates common Git operations, including:
- Loading environment variables
- Checking the status of the Git repository
- Staging files for commit
- Committing changes
- Renaming the current branch
- Updating the remote URL with credentials and pushing changes to GitHub

## Prerequisites

- Git must be installed on your machine.
- A `.env` file containing the necessary environment variables must be present in the same directory as the script.

## Environment Variables

Create a `.env` file in the same directory as this script with the following variables:

```bash
GITHUB_USERNAME=your_github_username
GITHUB_PASSWORD=your_github_password_or_personal_access_token
PROJECT_NAME=your_project_name
```


