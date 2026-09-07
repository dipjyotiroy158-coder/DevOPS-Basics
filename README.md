# Git Basics – First Lab

## Introduction

In the first lab, I learned the basic concepts of **Git and GitHub** and how to use Git through the terminal in VS Code. I also learned how to check whether Git is installed, configure Git, create a local repository, and clone an existing repository.

## 1. Checking Git Installation

First, I learned how to check whether Git is already installed on my computer.

The command used is:

```bash
git --version
```

If Git is installed, it displays the installed Git version.

If Git is not installed, Git can be downloaded and installed from the official Git website.

After installation, the `git --version` command can be used again to verify the installation.

## 2. Git Username and Email

Git requires a username and email address to identify who made changes to a repository.

To set the username:

```bash
git config --global user.name "Your Name"
```

To set the email:

```bash
git config --global user.email "your@email.com"
```

To check the configured username and email:

```bash
git config --global user.name
git config --global user.email
```

These details are associated with the commits made using Git.

## 3. Git Help

I learned how to get help about Git commands.

To see general Git help:

```bash
git help
```

We can also get help for a particular command:

```bash
git help <command>
```

For example:

```bash
git help clone
```

This helps us understand the usage and options of different Git commands.

## 4. Checking Remote Repository – Origin

I learned about **origin**, which is commonly used as the name of the remote repository connected to a local Git repository.

To see the remote repositories:

```bash
git remote -v
```

This displays the remote repository URL and shows whether it is used for fetching or pushing.

For example, a repository may have a remote named:

```text
origin
```

## 5. Initializing a Git Repository

I learned how to convert a normal project folder into a Git repository.

First, I created or opened a project folder and opened it in VS Code.

Then I used:

```bash
git init
```

This initializes a new Git repository in the current folder.

After running this command, Git creates a hidden `.git` directory that stores information required to track the project.

## 6. Cloning a Repository

I learned how to copy an existing repository from GitHub to my computer.

The command used is:

```bash
git clone <repository-url>
```

For example:

```bash
git clone https://github.com/username/repository.git
```

Cloning downloads the repository and its files to the local computer. It also connects the local repository with the remote repository.

## 7. Basic Git Commands Learned

| Command         | Purpose                                                  |
| --------------- | -------------------------------------------------------- |
| `git --version` | Checks whether Git is installed and displays its version |
| `git config`    | Configures Git settings                                  |
| `git help`      | Provides help about Git                                  |
| `git remote -v` | Shows connected remote repositories                      |
| `git init`      | Initializes a new Git repository                         |
| `git clone`     | Copies an existing repository to the computer            |

## Conclusion

In the first Git lab, I learned the basic setup and usage of Git. I learned how to check and install Git, configure my username and email, use Git help, check the remote repository named `origin`, initialize a local repository using `git init`, and clone an existing repository using `git clone`.

These commands helped me understand the basic workflow of using Git for **version control and managing projects**.
