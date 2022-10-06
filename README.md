# Hacktoberfest'22

## Git/GitHub Session
This is a Repo for the Session on Git/GitHub.

[![MasterHead](https://raw.githubusercontent.com/kunal-mahatha/git-session/master/banner.png)](https://username.github.io)

## What is Git ?
Git is a version control system that lets you manage and keep track of your source code history.

## What is GitHub ?
GitHub is a cloud-based hosting service that lets you manage Git repositories. If you have open-source projects that use Git, then GitHub is designed to help you better manage them.

## What’s a repository?
A repository, or Git project, encompasses the entire collection of files and folders associated with a project, along with each file’s revision history.

## Using Git
## Basic Commands
* `pwd` prints working directory
* `ls` lists all the files and folders
* `cd` change directory
* `mkdir` makes or creates directory
* `touch` creates file
* `cd..` go back
* `rm` removes file
* `rm-rf` removes folder
* `mv` rename or move file

## Basic Git Commands
- `git init` initializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.

- `git clone` creates a local copy of a project that already exists remotely. The clone includes all the project’s files, history, and branches.

- `git add` stages a change. Git tracks changes to a developer’s codebase, but it’s necessary to stage and take a snapshot of the changes to include them in the project’s history. This command performs staging, the first part of that two-step process. Any changes that are staged will become a part of the next snapshot and a part of the project’s history. Staging and committing separately gives developers complete control over the history of their project without changing how they code and work.

- `git commit` saves the snapshot to the project history and completes the change-tracking process. In short, a commit functions like taking a photo. Anything that’s been staged with git add will become a part of the snapshot with git commit.

- `git status` shows the status of changes as untracked, modified, or staged.

- `git branch` shows the branches being worked on locally.

- `git merge` merges lines of development together. This command is typically used to combine changes made on two distinct branches. For example, a developer would merge when they want to combine changes from a feature branch into the main branch for deployment.

- `git pull` updates the local line of development with updates from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in their local environment.

- `git push` updates the remote repository with any commits made locally to a branch.

## GitHub Workfow
The GitHub flow is a lightweight, branch-based workflow built around core Git commands used by teams around the globe—including ours.

The GitHub flow has six steps, each with distinct benefits when implemented:

1. **Create a branch**: Topic branches created from the canonical deployment branch (usually main) allow teams to contribute to many parallel efforts. Short-lived topic branches, in particular, keep teams focused and results in quick ships.

2. **Add commits**: Snapshots of development efforts within a branch create safe, revertible points in the project’s history.

3. **Open a pull request**: Pull requests publicize a project’s ongoing efforts and set the tone for a transparent development process.

4. **Discuss and review code**: Teams participate in code reviews by commenting, testing, and reviewing open pull requests. Code review is at the core of an open and participatory culture.

5. **Merge**: Upon clicking merge, GitHub automatically performs the equivalent of a local ‘git merge’ operation. GitHub also keeps the entire branch development history on the merged pull request.

6. **Deploy**: Teams can choose the best release cycles or incorporate continuous integration tools and operate with the assurance that code on the deployment branch has gone through a robust workflow.

# Explore More
To Learn Git/GitHub in Detail [Click here](https://classroom.udacity.com/courses/ud123). 

# Author
[Suraj Kumar Barnwal](https://github.com/RedocamaI)
