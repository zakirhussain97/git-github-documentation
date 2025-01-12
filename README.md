# git-github-documentation
Git and GitHub Onboarding Documentation

# Welcome to Git and GitHub!

## Introduction
Welcome! This documentation is designed to help new developers get started with Git and GitHub, essential tools for version control and collaboration in our projects. By following this guide, you'll learn how to set up Git, use basic commands, and collaborate effectively using GitHub.

## Basics of Git and GitHub
### What is Git?
Git is a distributed version control system that allows multiple developers to work on a project simultaneously without overwriting each other's changes. It helps track changes, revert to previous states, and collaborate efficiently.

### What is GitHub?
GitHub is a web-based platform that hosts Git repositories. It provides tools for collaboration, such as pull requests, code reviews, and issue tracking, making it easier for teams to work together on projects.

## Installation and Setup
### Installing Git
#### Windows
1. Download the Git installer from [git-scm.com](https://git-scm.com/download/win).
2. Run the installer and follow the prompts.
3. Verify the installation by running `git --version` in the command prompt.

#### macOS
1. Install Git using Homebrew: `brew install git`.
2. Verify the installation by running `git --version` in the terminal.

#### Linux
1. Install Git using the package manager: `sudo apt-get install git` (Debian/Ubuntu) or `sudo yum install git` (Fedora).
2. Verify the installation by running `git --version` in the terminal.

### Configuring Git
Set your user name and email:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"


```

### Creating a GitHub Account
1. Go to [github.com](https://github.com) and sign up for a new account.
2. Follow the prompts to complete the registration process.

## Cloning the ChaiCode Repository
1. Open your terminal or command prompt.
2. Run the following command to clone the repository:
```bash
git clone https://github.com/demo/example-repo.git
```
3. Navigate into the cloned repository folder:
```bash
cd example-repo
```

## Basic Git Commands
### Commonly Used Commands
- Check the status of your repository:
  ```bash
  git status
  ```
- Add changes to the staging area:
  ```bash
  git add <file>
  ```
- Commit changes with a message:
  ```bash
  git commit -m "message"
  ```
- Push changes to the remote repository:
  ```bash
  git push
  ```
- Pull updates from the remote repository:
  ```bash
  git pull
  ```
- View the commit history:
  ```bash
  git log
  ```

## Commit Message Rules
- Use the present tense ("Add feature" not "Added feature").
- Capitalize the first letter.
- Keep the message short (50 characters or less).
- Use prefixes like `fix:`, `feat:`, `chore:`, `docs:` for categorization.

### Examples
```bash
feat: Add tea selection feature
fix: Resolve login issue for tea enthusiasts
docs: Update README with chai varieties
```

## Branching Workflow
### Branching Strategy
At ChaiCode, we use the following branching strategy:
- `main`: The stable production branch.
- `development`: The branch for ongoing development.
- `feature/*`: Branches for new features.

### Creating and Switching Branches
- Create a new branch:
  ```bash
  git branch feature/tea-menu
  ```
- Switch to the new branch:
  ```bash
  git checkout feature/tea-menu
  ```

### Merging Branches and Resolving Conflicts
- Merge a feature branch into `development`:
  ```bash
  git checkout development
  git merge feature/tea-menu
  ```
- Resolve any conflicts that arise during the merge.

## Pull Requests (PR)
### Creating a Pull Request
1. Push your feature branch to GitHub.
2. Go to the repository on GitHub and click "New pull request".
3. Select your feature branch and provide a description of the changes.
4. Request a code review from your team members.

## Best Practices
- Commit regularly with descriptive messages.
- Pull updates frequently to avoid conflicts.
- Follow the commit message rules and branching strategy.

By following this guide, you'll be well on your way to mastering Git and GitHub. Happy coding!
```
