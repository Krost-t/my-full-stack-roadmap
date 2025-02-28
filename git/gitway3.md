
# 3. Basic Git Commands

## 3.1 git init

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

## 3.2 git clone

This command allows you to clone a remote repository to your local machine. It creates a full copy of the project.

Example:

1. Go to a project on GitHub, for example, [https://github.com/username/repository](https://github.com/username/repository).
2. Copy the project URL.
3. In your terminal, type:
    ```bash
    git clone https://github.com/username/repository.git
    ```

This creates a copy of the repository on your machine, with the entire version history.

## 3.3 git status

This command shows the current state of your repository: modified files, files waiting to be committed, etc.

Example:
    ```bash
    git status
    ```

It will tell you, for example:

- Untracked files.
- Modified files.
- Files ready to be committed.

## 3.4 git add

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

## 3.5 git commit

A commit is a record of changes made. Each commit must have a message describing what was changed.

Example:

1. After adding your files:
    ```bash
    git commit -m "Added search feature"
    ```

This records your changes in the history with a commit message.

## 3.6 git push

This command sends your local commits to a remote repository (like GitHub).

Example:

1. Push your changes to the remote repository:
    ```bash
    git push origin main
    ```

This sends the commits made on your local `main` branch to GitHub.

## 3.7 git pull

This command fetches the latest changes from a remote repository and merges them into your local branch.

Example:
    ```bash
    git pull origin main
    ```

This fetches changes made by other users and applies them to your local branch.
