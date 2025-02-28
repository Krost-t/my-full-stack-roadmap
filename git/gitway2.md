
# 2. Installation and Configuration of Git

## 2.1 How to Install Git?

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

## 2.2 Initial Git Configuration

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

## 2.3 Advanced Configurations

1. **Change Default Editor:** If you prefer to use a specific text editor for writing commit messages, you can set it up. For example, to use **Nano**, enter the following command:
    ```bash
    git config --global core.editor "nano"
    ```

2. **Configure Remote Repositories:** If you're working with remote repositories, you can configure the default URL for your remote repository. For example, to link your local repository to a GitHub remote repository:
    ```bash
    git remote set-url origin https://github.com/username/repository.git
    ```

These advanced configurations allow you to further customize your Git experience and better manage collaborative projects.
