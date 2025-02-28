
# 4. Branch Management

## 4.1 Create a Branch

Branches allow you to work on different versions of your project in isolation.

Example:

To create a new branch:
```bash
git branch new-branch
```

## 4.2 Switch Between Branches

Once a branch is created, you can switch between branches using the `git checkout` command.

Example:

To switch to the `new-branch`:
```bash
git checkout new-branch
```

## 4.3 Merge Branches

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

## 4.4 Delete Branches

Once a branch is merged, you can delete it to keep your repository clean.

Example:

To delete the `new-branch`:
```bash
git branch -d new-branch
```

