# Git Learning Journey

[Previous content remains unchanged...]

## 2. Setting up Git: Configuration and Initialization

Before we start using Git, we need to set it up properly. This involves configuring your identity and initializing a Git repository for your project.

### 2.1 Configuring Git

First, let's configure your name and email address. Git uses this information to associate commits with an identity.

In VSCode:
1. Open the integrated terminal (Ctrl+` or View > Terminal)
2. Enter the following commands:

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

CLI Equivalent:
The process is the same in any terminal:

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

### 2.2 Initializing a Git Repository

Now, let's initialize a new Git repository for your project.

In VSCode:
1. Open the folder for your project in VSCode.
2. Click on the Source Control icon in the left sidebar (Ctrl+Shift+G).
3. Click on "Initialize Repository" button.

CLI Equivalent:
In your project directory, run:

```bash
git init
```

This command creates a new .git subdirectory in your project folder, which contains all the necessary metadata for the repository.

### 2.3 Checking Git Status

Let's verify that our repository is set up correctly.

In VSCode:
1. The Source Control view will show you an overview of your changes.
2. You can see which files are untracked, modified, or staged.

CLI Equivalent:
Run the following command:

```bash
git status
```

This command shows the current state of your working directory and staging area.

Now that we have set up our Git repository, in the next section, we'll learn about the basic Git workflow: adding, committing, and checking the status of our files.

Let's move on to the next step: Basic Git Workflow.