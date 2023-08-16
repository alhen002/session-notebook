# git cli and remote

## git basic commands

```bash
git init
```

This command initializes a new Git repository in the current directory. Use this command when you want to start tracking changes to a new project or when you want to create a local copy of an existing repository.

```bash
git add
```

This command adds changes made to files in the working directory to the staging area in preparation for a commit. You can add specific files or use a wildcard to add all changes. For example, "git add file.txt" adds changes made to file.txt to the staging area, while "git add \*" adds changes made to all files in the current directory to the staging area.

```bash
git commit
```

This command records changes made to the repository. You must provide a commit message that describes the changes made. For example, "git commit -m 'Added new feature'". It's important to write clear and concise commit messages that accurately describe the changes made. This makes it easier to understand the history of the repository and to track changes over time.

```bash
git log
```

This command shows a list of all commits made to the current repository, including the commit message, author, and date. You can use various options with this command to customize the output, such as showing a specific number of commits, filtering by author or date, or formatting the output in a specific way.

```bash
git status
```

This command shows the current status of the Git repository, including any changes that are staged or unstaged, and any files that have not been tracked by Git. It's a useful command to run frequently to keep track of changes to your repository and to ensure that you are always working with the latest version of your files.

```bash
git push
```

This command pushes changes made in the local repository to the remote repository. You must specify the name of the remote repository and the branch you want to push to. For example, "git push origin main" pushes changes made in the local repository to the "main" branch of the "origin" remote repository. It's important to pull changes from the remote repository before pushing changes to avoid conflicts and ensure that your local repository is up-to-date with the remote repository.

```bash
git pull
```

This command pulls changes made in the remote repository to the local repository. You must specify the name of the remote repository and the branch you want to pull from. For example, "git pull origin main" pulls changes made in the "main" branch of the "origin" remote repository to the local repository. It's important to pull changes before making changes to avoid conflicts and ensure that you are working with the latest version of the files.

```bash
git switch -c header
```

This command creates a new branch named "header" and switches to it. Use this command when you want to start working on a new feature or bugfix without affecting the main branch. The "-c" flag is used to create a new branch.

```bash
git switch

```

This command switches to an existing branch. You must specify the name of the branch you want to switch to. For example, "git switch main" switches to the "main" branch. Use this command when you want to switch between different branches in your repository.

```bash
git branch
```

This command lists all branches in the current repository. Use this command to see all the available branches and to help you keep track of your work. You can use various options with this command to customize the output, such as showing the last commit on each branch or filtering by branch name.

```bash
git branch -d name

```

This command deletes the branch named "name". Use this command when you no longer need a branch that you have created or merged into another branch. It's important to ensure that you are not deleting a branch that contains changes that have not been merged into another branch, as these changes will be lost.
