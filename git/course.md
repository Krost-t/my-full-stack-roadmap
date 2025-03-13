# 📚 Git & GitHub Course Outline

Welcome to my comprehensive Git & GitHub course! This outline will guide you through the essential topics I have learned to become proficient in version control and collaboration.

## Course Modules

- [📚 Git \& GitHub Course Outline](#-git--github-course-outline)
  - [Course Modules](#course-modules)
  - [1. Introduction to Git and GitHub](#1-introduction-to-git-and-github)
    - [1.1 What is Git?](#11-what-is-git)
      - [Why Use Git?](#why-use-git)
      - [Key Features of Git:](#key-features-of-git)
    - [1.2 What is GitHub?](#12-what-is-github)
      - [Main Features:](#main-features)
      - [Difference between Git and GitHub:](#difference-between-git-and-github)
    - [1.3 Why Use Git and GitHub?](#13-why-use-git-and-github)
      - [Advantages of Git:](#advantages-of-git)
      - [Advantages of GitHub:](#advantages-of-github)
      - [Use Case Examples:](#use-case-examples)
  - [2. Installation and Configuration of Git](#2-installation-and-configuration-of-git)
    - [2.1 How to Install Git?](#21-how-to-install-git)
    - [2.2 Initial Git Configuration](#22-initial-git-configuration)
    - [2.3 Advanced Configurations](#23-advanced-configurations)
  - [3. Basic Git Commands](#3-basic-git-commands)
    - [3.1 git init](#31-git-init)
    - [3.2 git clone](#32-git-clone)
    - [3.3 git status](#33-git-status)
    - [3.4 git add](#34-git-add)
    - [3.5 git commit](#35-git-commit)
    - [3.6 git push](#36-git-push)
    - [3.7 git pull](#37-git-pull)
  - [4. Branch Management](#4-branch-management)
    - [4.1 Create a Branch](#41-create-a-branch)
    - [4.2 Switch Between Branches](#42-switch-between-branches)
    - [4.3 Merge Branches](#43-merge-branches)
    - [4.4 Delete Branches](#44-delete-branches)
  - [5. Best Practices for Commits](#5-best-practices-for-commits)
    - [5.1 Writing Clear Commit Messages](#51-writing-clear-commit-messages)
    - [5.2 Using Commit Conventions](#52-using-commit-conventions)
    - [5.3 Commit Frequency](#53-commit-frequency)
  - [6. Conflict Management](#6-conflict-management)
    - [6.1 Understanding Merge Conflicts](#61-understanding-merge-conflicts)
    - [6.2 Resolving Conflicts](#62-resolving-conflicts)
    - [Additional Tips](#additional-tips)
  - [7. Advanced Git Usage](#7-advanced-git-usage)
    - [7.1 Rebasing](#71-rebasing)
    - [7.2 Cherry-picking](#72-cherry-picking)
    - [7.3 Stashing](#73-stashing)
    - [7.4 Tagging](#74-tagging)
  - [8. Collaborating with GitHub](#8-collaborating-with-github)
    - [8.1 Creating a Repository on GitHub](#81-creating-a-repository-on-github)
    - [8.2 Forking a Repository](#82-forking-a-repository)
    - [8.3 Creating a Pull Request (PR)](#83-creating-a-pull-request-pr)
    - [8.4 Reviewing a Pull Request](#84-reviewing-a-pull-request)
  - [9. Automation with GitHub Actions](#9-automation-with-github-actions)
    - [9.1 Introduction to GitHub Actions](#91-introduction-to-github-actions)
    - [9.2 Creating a Basic Workflow](#92-creating-a-basic-workflow)
    - [9.3 Advanced Workflow Examples](#93-advanced-workflow-examples)
  - [10. Security and Best Practices](#10-security-and-best-practices)
    - [10.1 Managing SSH Keys](#101-managing-ssh-keys)
    - [10.2 Using GitHub Tokens](#102-using-github-tokens)
    - [10.3 Securing Your Repository](#103-securing-your-repository)


## 1. Introduction to Git and GitHub

### 1.1 What is Git?
Git is a **distributed version control system (VCS)** created by **Linus Torvalds** in 2005. It helps developers track changes to files, manage source code history, and collaborate effectively on software projects.

#### Why Use Git?
- Track the history of code changes
- Facilitate collaboration between developers
- Restore previous versions of the project
- Work simultaneously on different features using branches
- Distributed system (each developer has a full copy of the repository)
- Reliable and secure data management

#### Key Features of Git:
- **Version tracking**: Every change is recorded with author, timestamp, and message
- **Branching and Merging**: Develop new features without affecting the main codebase
- **Distributed Nature**: No single point of failure
- **Lightweight and Fast**: Optimized for performance

---

### 1.2 What is GitHub?
**GitHub** is a **cloud-based platform** that hosts Git repositories, enabling developers to collaborate, share code, and manage software projects online. Founded in 2008, GitHub is widely used by the open-source community and private companies.

#### Main Features:
- Git Repository Hosting
- Collaboration through **Pull Requests** and **Code Reviews**
- **Issues Tracking** to manage tasks and bugs
- **GitHub Actions** for automation (CI/CD pipelines)
- Project Management Tools (Kanban boards)
- **Security & Access Management**
- Documentation hosting via GitHub Pages

#### Difference between Git and GitHub:
| Git                 | GitHub              |
|-------------------|-------------------|
| Version control software | Cloud-based hosting service |
| Works locally or remotely | Works online with remote repositories |
| Command-line interface   | Web-based graphical interface |
| Open Source           | Provides free and paid services |

---

### 1.3 Why Use Git and GitHub?

#### Advantages of Git:
- Fast and lightweight
- Full branch management system
- Cross-platform compatibility (Windows, Linux, MacOS)
- Open Source and free
- Secure and distributed system

#### Advantages of GitHub:
- Global collaboration with developers worldwide
- User-friendly web interface
- Integration with third-party tools (CI/CD, Slack, Jira, etc.)
- Task automation via **GitHub Actions**
- Access and permission management
- Community support for open-source projects

#### Use Case Examples:
- Collaborative software development
- Open-source project management
- Project documentation and versioning
- Automatic deployment pipelines
- Bug tracking and issue management



## 2. Installation and Configuration of Git

### 2.1 How to Install Git?

Before you can use Git, you need to install it on your machine. Here are the installation steps based on your operating system:

- **On macOS:**
    1. Open a terminal and type the following command to install Git via Homebrew:
    ```bash
    brew install git
    ```
    2. If you don't have Homebrew installed, you can get it by following the instructions here: [https://brew.sh/](https://brew.sh/).

- **On Linux (Ubuntu):**
    1. Open a terminal and type the following command to install Git:
    ```bash
    sudo apt-get install git
    ```

- **On Windows:**
    1. Download the Git installer from [https://git-scm.com/download/win](https://git-scm.com/download/win).
    2. Run the installer and follow the setup steps. During installation, you can choose additional options, such as integrating Git into your text editor or adding Git to the system path.

### 2.2 Initial Git Configuration

Once Git is installed, you need to configure your personal information. This allows Git to link your commits to your identity. To do this, follow these steps:

1. Open your terminal and enter the following command to set your username:
    ```bash
    git config --global user.name "Your Name"
    ```

2. Next, configure your email address so that Git can associate your commits with that address:
    ```bash
    git config --global user.email "your.email@example.com"
    ```

This information will be used to link your commits to your identity, and it will appear in the history of your project.

### 2.3 Advanced Configurations

1. **Change Default Editor:** If you prefer to use a specific text editor for writing commit messages, you can set it up. For example, to use **Nano**, enter the following command:
    ```bash
    git config --global core.editor "nano"
    ```

2. **Configure Remote Repositories:** If you're working with remote repositories, you can configure the default URL for your remote repository. For example, to link your local repository to a GitHub remote repository:
    ```bash
    git remote set-url origin https://github.com/username/repository.git
    ```

These advanced configurations allow you to further customize your Git experience and better manage collaborative projects.


## 3. Basic Git Commands

### 3.1 git init

This command initializes a new Git repository in the current directory.

Example:

1. Go to your project directory:
    ```bash
    cd my-project
    ```

2. Initialize the repository:
    ```bash
    git init
    ```

This creates a `.git` directory that contains all the history and metadata Git needs to track changes.

### 3.2 git clone

This command allows you to clone a remote repository to your local machine. It creates a full copy of the project.

Example:

1. Go to a project on GitHub, for example, [https://github.com/username/repository](https://github.com/username/repository).
2. Copy the project URL.
3. In your terminal, type:
    ```bash
    git clone https://github.com/username/repository.git
    ```

This creates a copy of the repository on your machine, with the entire version history.

### 3.3 git status

This command shows the current state of your repository: modified files, files waiting to be committed, etc.

Example:
    ```bash
    git status
    ```

It will tell you, for example:

- Untracked files.
- Modified files.
- Files ready to be committed.

### 3.4 git add

This command adds files or changes to the staging area, preparing them for commit.

Example:

1. Add a specific file:
    ```bash
    git add file.txt
    ```

2. Add all modified files:
    ```bash
    git add .
    ```

This prepares the files so you can commit them.

### 3.5 git commit

A commit is a record of changes made. Each commit must have a message describing what was changed.

Example:

1. After adding your files:
    ```bash
    git commit -m "Added search feature"
    ```

This records your changes in the history with a commit message.

### 3.6 git push

This command sends your local commits to a remote repository (like GitHub).

Example:

1. Push your changes to the remote repository:
    ```bash
    git push origin main
    ```

This sends the commits made on your local `main` branch to GitHub.

### 3.7 git pull

This command fetches the latest changes from a remote repository and merges them into your local branch.

Example:
    ```bash
    git pull origin main
    ```

This fetches changes made by other users and applies them to your local branch.


## 4. Branch Management

### 4.1 Create a Branch

Branches allow you to work on different versions of your project in isolation.

Example:

To create a new branch:
```bash
git branch new-branch
```

### 4.2 Switch Between Branches

Once a branch is created, you can switch between branches using the `git checkout` command.

Example:

To switch to the `new-branch`:
```bash
git checkout new-branch
```

### 4.3 Merge Branches

Merging allows you to integrate changes from one branch into another.

Example:

To merge the `new-branch` into `main`:

1. First, switch to the target branch (`main`):
    ```bash
    git checkout main
    ```

2. Then, merge `new-branch`:
    ```bash
    git merge new-branch
    ```

### 4.4 Delete Branches

Once a branch is merged, you can delete it to keep your repository clean.

Example:

To delete the `new-branch`:
```bash
git branch -d new-branch
```

## 5. Best Practices for Commits

### 5.1 Writing Clear Commit Messages

Commit messages should be informative and concise. A good convention to follow is:

- **Title**: Summarize what you have done in 50 characters or less.
- **Body (optional)**: Explain why you made these changes, providing more details if necessary.

Example:

```bash
git commit -m "Fix homepage loading bug"
```

### 5.2 Using Commit Conventions

There are conventions like **Conventional Commits** or **Commitizen** that standardize commit messages for a project. These conventions help maintain a consistent history and improve collaboration.

Example format:

- `feat`: Add a new feature (e.g., `feat: add search functionality`)
- `fix`: Fix a bug (e.g., `fix: resolve display issue`)
- `docs`: Documentation updates
- `refactor`: Code refactoring without changing functionality
- `test`: Adding or modifying tests
- `chore`: Routine tasks and maintenance

### 5.3 Commit Frequency

Commit frequently to keep a detailed history of your work. However, avoid committing after every minor change. Commit at each logical point in your work, such as after completing a feature or fixing a bug.

Frequent, meaningful commits make it easier to understand the project's evolution and simplify debugging.


## 6. Conflict Management

### 6.1 Understanding Merge Conflicts

Merge conflicts occur when Git cannot automatically merge changes from two branches. This typically happens when two people have modified the same line in a file or when one person edits a file while another deletes it.

### 6.2 Resolving Conflicts

When Git detects a conflict, it marks the affected files as having conflicts.

To resolve conflicts:

1. Open the conflicted files.
2. Look for the conflict markers:
   - `<<<<<<< HEAD`: Indicates the current branch's changes.
   - `=======`: Separates the two conflicting changes.
   - `>>>>>>> branch_name`: Indicates the incoming branch's changes.
3. Edit the file to select which version to keep or combine both versions.
4. Save the changes.

Once the conflicts are resolved, stage the files using:

```bash
git add conflicted_file
```

Then, complete the merge by committing the changes:

```bash
git commit -m "Conflict resolution"
```

### Additional Tips
- Use tools like `git diff` or GUI-based merge tools (such as `GitKraken` or `VSCode`) to visualize conflicts more easily.
- Regularly pull changes from the remote branch to minimize conflicts.
- Communicate with your team to avoid working on the same file simultaneously.

## 7. Advanced Git Usage

### 7.1 Rebasing

Rebasing allows you to rewrite the history of a branch so that it includes the commits from another branch without performing a merge. This creates a linear project history, which can make it easier to follow.

Example:

```bash
git rebase main
```

This command applies your commits on top of the commits from the `main` branch.

**Tip:** Use `git rebase -i` (interactive mode) to edit, reorder, or squash commits during the rebase process.

### 7.2 Cherry-picking

Cherry-picking allows you to apply a specific commit from one branch onto your current branch. This is particularly useful when you want to apply a fix without merging the entire branch.

Example:

```bash
git cherry-pick <commit-hash>
```

If there are conflicts during the cherry-pick process, Git will pause and allow you to resolve them before continuing.

### 7.3 Stashing

Stashing temporarily saves uncommitted changes, allowing you to switch branches or perform other tasks without committing incomplete work.

Example:

Save current changes:

```bash
git stash
```

List all stashes:

```bash
git stash list
```

Apply the most recent stash and remove it from the stash list:

```bash
git stash pop
```

Apply a specific stash without removing it from the stash list:

```bash
git stash apply stash@{n}
```

### 7.4 Tagging

Tags are used to mark important points in the repository history, often representing software versions (e.g., `v1.0`, `v2.0`).

Example:

Create a lightweight tag:

```bash
git tag v1.0
```

List all tags:

```bash
git tag
```

Create an annotated tag with a message:

```bash
git tag -a v1.0 -m "Version 1.0 release"
```

Push tags to the remote repository:

```bash
git push origin --tags
```


## 8. Collaborating with GitHub

### 8.1 Creating a Repository on GitHub

A GitHub repository allows you to centralize your code and collaborate with other developers.

Steps to create a repository:

1. Go to GitHub (https://github.com) and log in to your account.
2. Click the "New" button in the top-left corner or go directly to the new repository creation page: Create a repository.
3. Fill in the information:
   - Repository Name: Choose a name for your project.
   - Description: Briefly describe the project (optional).
   - Public/Private: Choose whether you want the repository to be public or private.
4. Click "Create repository."

Example command to link your local repository to GitHub:

```bash
git remote add origin https://github.com/username/my-repository.git
git push -u origin main
```

This will link your local repository to GitHub and push the code to the remote repository.

### 8.2 Forking a Repository

Forking is a feature on GitHub that allows you to create a personal copy of a project to propose changes without affecting the original repository.

Steps to fork a repository:

1. Go to the repository you want to fork on GitHub.
2. Click the "Fork" button at the top-right corner of the repository page.
3. GitHub creates a copy of the repository in your own user space.

Example:

After forking a repository, you can clone your copy to your local machine:

```bash
git clone https://github.com/your-username/my-repository.git
```

### 8.3 Creating a Pull Request (PR)

A Pull Request (PR) is used to propose changes in a GitHub repository, typically from a branch or a fork. The PR allows others to review and discuss your changes before integrating them into the main project.

Steps to create a PR:

1. Start by forking the repository or creating a branch to make modifications.
2. Once you have made the changes locally, push your modifications to GitHub:

   ```bash
git push origin feature-branch
```

3. Go to GitHub and open your repository; you will see a "Compare & Pull Request" button.
4. Click it and fill in the required information (description, base, and target branch).
5. Click "Create Pull Request."

Example:

Once the PR is created, the repository maintainers can review it, leave comments, and accept it if the changes are satisfactory.

### 8.4 Reviewing a Pull Request

Code review is an essential aspect of GitHub, where project maintainers examine the changes proposed by contributors.

Steps to review a PR:

1. Go to the Pull Requests page of the repository (Pull requests tab on GitHub).
2. Select a PR and examine the modified files.
3. You can add inline comments on specific lines of code.
4. Once satisfied with the PR, you can merge it by clicking "Merge pull request."

Example:

You can also add a general comment or ask questions before accepting the PR.


## 9. Automation with GitHub Actions

### 9.1 Introduction to GitHub Actions

GitHub Actions allows you to automate tasks such as testing, deployments, and other processes on every change in your repository.

Workflows are defined in `.yml` files located in the `.github/workflows/` directory of your repository.

### 9.2 Creating a Basic Workflow

A GitHub Actions workflow defines a set of tasks to run on a specific action (e.g., on a push).

Example workflow for a Python project:

1. Create a file in `.github/workflows/ci.yml` in your repository.
2. Add the following content for a workflow that runs tests on every push:

```yaml
name: Continuous Integration

on:
  push:
    branches:
      - main

jobs:
  test:
    runs-on: ubuntu-latest

    steps:
    - name: Checkout code
      uses: actions/checkout@v2

    - name: Set up Python
      uses: actions/setup-python@v2
      with:
        python-version: '3.8'

    - name: Install dependencies
      run: |
        python -m pip install --upgrade pip
        pip install -r requirements.txt

    - name: Run tests
      run: |
        pytest
```

Explanation:

- `on: push` indicates that this workflow triggers on every push to the `main` branch.
- `steps` define the different actions to perform, such as setting up Python, installing dependencies, and running tests.

### 9.3 Advanced Workflow Examples

You can create more complex workflows, such as continuous deployment pipelines or other automated processes.

Example: Workflow for Deployment to Heroku

```yaml
name: Deploy to Heroku

on:
  push:
    branches:
      - main

jobs:
  deploy:
    runs-on: ubuntu-latest

    steps:
    - name: Checkout code
      uses: actions/checkout@v2

    - name: Set up Heroku CLI
      uses: akshnz/heroku-cli-action@v1.0.0

    - name: Login to Heroku
      run: echo "${{ secrets.HEROKU_API_KEY }}" | heroku auth:token

    - name: Deploy to Heroku
      run: git push https://git.heroku.com/<your-app-name>.git main
```

This workflow deploys your application to Heroku on every push to the `main` branch.


## 10. Security and Best Practices

### 10.1 Managing SSH Keys

SSH keys allow you to establish a secure connection with GitHub without needing to enter your password for every operation. They are essential for managing private repositories.

Steps to configure an SSH key:

1. Open your terminal and generate a new SSH key:

   ```bash
ssh-keygen -t rsa -b 4096 -C "your.email@example.com"
```

   Press Enter to accept the default file location.
2. Once the key is generated, copy it to your clipboard:

   ```bash
cat ~/.ssh/id_rsa.pub
```

3. Go to GitHub, navigate to Settings > SSH and GPG keys, and add a new SSH key by pasting your public key.

### 10.2 Using GitHub Tokens

GitHub tokens are used to authenticate with the GitHub API and perform actions like managing repositories, issues, etc., without exposing your password.

Creating a GitHub token:

1. Go to Settings > Developer settings > Personal access tokens.
2. Click "Generate new token."
3. Select the permissions you want to grant to this token (e.g., for accessing private repositories).
4. Copy the generated token.

Example of using a token:

You can use this token to perform actions via the GitHub API or as an authentication method in a script, like this:

```bash
curl -H "Authorization: token YOUR_GITHUB_TOKEN" https://api.github.com/user/repos
```

### 10.3 Securing Your Repository

It is important to secure your repositories, especially if you are working with sensitive information.

Some best practices:

- Use private repositories for sensitive projects.
- Enable two-factor authentication (2FA) on your GitHub account.
- Manage access: Limit repository access to only necessary individuals.
- Never include sensitive information (API keys, passwords, etc.) in your code. Use `.env` files or GitHub secrets to manage sensitive information.
