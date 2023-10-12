# Git Project
Git is a distributed version control system that allows developers to track changes in their codebase over time. It provides a mechanism for multiple contributors to collaborate on software development, enabling them to make changes to the code, track these changes, and merge their work seamlessly. Git records each change as a commit, which serves as a snapshot of the code at a specific point in time.

GitHub, on the other hand, is a web-based platform that utilizes Git for version control. It hosts Git repositories and provides a collaborative environment for software development projects. Developers can use GitHub to store, share, and collaborate on code, making it a popular platform for open-source projects and team-based software development. GitHub offers features such as issue tracking, pull requests, and integration with various tools to enhance the development and collaboration process.

## Initializing a Repository and Making Commits
`git init` is a Git command that initializes a new repository for version control in a specific directory. When you run git init in a directory, Git creates a hidden subdirectory called .git, where it stores all the configuration, tracking, and version control information for the project. This command essentially tells Git to start managing the project's files, allowing you to track changes and create commits. Once a repository is initialized, you can use other Git commands like git add and git commit to begin tracking and managing your project's source code.

> To initialize a Git repository for a project, follow these steps:
* Open a Terminal: Open your command line terminal on your computer.
* Navigate to Your Project's Directory: Use the cd command to navigate to the directory where your project is located. For example: `cd /path/to/your/project`
![cd /path/to/your/project](./img/0.png)
* Initialize a Git Repository: Use the git init command to create a new Git repository in the current directory: `git init`
![git init](./img/1.png)

## Making your first Commit
Making your first commit in Git is a crucial step in tracking and recording changes in your project. After initializing a Git repository and making changes to your code, you can use the git add command to stage the changes you want to include in the commit. For example, `git add .` stages all changes in the current directory. Once the changes are staged, you can commit them using the git commit command, along with a descriptive message using the -m flag, such as `git commit -m "Initial commit"`. This message should briefly summarize the changes or the purpose of the commit, providing a clear record of your project's history.

> To make your first commit:
* Adding files to the staging area by running: `git add .`
* Committing changes with a message by running: `git commit -m "first commit"`
![git commit](./img/2.png)

## Working with branches
Working with branches in Git allows you to work on different features or aspects of your project independently. You can create a new branch using the `git checkout -b branch-name` command, where branch-name is the name of the new branch. This branch will be based on the current state of your project. To switch between branches, use `git checkout branch-name`. You can develop new features or make changes in separate branches without affecting the main branch (often called "master" or "main"). Once you are satisfied with your changes, you can merge or integrate them into the main branch, ensuring a controlled and organized development workflow.

* Adding a remote repository named "origin":            `git remote add origin https://github.com/atubak400/Git-Project.git`
* Renaming the default branch from "master" to "main":  `git branch -M main`
* Pushing the changes to the remote repository and setting up tracking: `git push -u origin main`
* Checking the available branches: `git branch`
* Cloning the remote repository to a new directory: `git clone https://github.com/atubak400/Git-Project.git`




