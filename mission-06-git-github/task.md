# Mission 6 — Git and GitHub

## Task 6.1 — Understand the Basic Git Workflow

Git is a version control system that records changes to files. It allows us to track previous versions, review changes and manage project development.

| Git operation | What it does in my own words |
|---|---|
| Check repository status | `git status` shows which files have been modified, staged, or are untracked. |
| Stage selected changes | `git add <file>` selects a file's changes to be included in the next commit. |
| Create a commit | `git commit -m 'message'` records the staged changes in the repository's history. |
| View commit history | `git log --oneline` displays previous commits in a compact format. |

### Difference Between Staging and Committing

Staging means selecting the changes that I want to include in a commit. Committing records those staged changes as a saved point in the Git history.

Staging does not permanently record the changes in the commit history. A commit is created only after the staged changes are committed.

## Task 6.2 — Create and Use a Branch

A branch is a separate line of development within a Git repository. It allows changes to be made independently without directly modifying the main branch.

### Steps performed

1. Created a new branch named `update-about`.
2. Added a section titled **My Learning** to the root `README.md`.
3. Described the concepts learned so far.
4. Checked the repository status using `git status`.
5. Staged the README change using `git add README.md`.
6. Committed the change with a meaningful commit message.
7. Published the branch to GitHub.

**Branch name:** `update-about`

**Commit message:** To be recorded after completing the commit.

**Branch publication:** To be confirmed after pushing to GitHub.

## Task 6.3 — Create a Pull Request

### Objective
Create a Pull Request from the `update-about` branch into the `main` branch and understand how changes are reviewed before being merged.

### Steps performed
1. Published the `update-about` branch to GitHub.
2. Opened the repository on GitHub.
3. Selected `main` as the base branch and `update-about` as the compare branch.
4. Created a Pull Request describing the changes made to the root README.
5. Reviewed the changes under the Files changed section.
6. Checked the Pull Request status.

### Branch and Pull Request

**Branch:** A branch is a separate line of development that allows changes to be made without directly modifying the main branch.

**Pull Request:** A Pull Request is a request to review and merge changes from one branch into another.

### Why branches and Pull Requests are useful

Branches allow developers to work on changes independently without affecting the main version of a project. Pull Requests allow those changes to be reviewed, discussed and checked before they are merged. This makes collaboration more organised and helps prevent mistakes.

### Pull Request details

- **Source branch:** `update-about`
- **Target branch:** `main`
- **Purpose:** Add a "My Learning" section to the root README.
- **Pull Request status:** To be confirmed.
- **Merge status:** To be confirmed.

## Task 6.4 — Git Command Glossary

| Git operation | Command | Explanation |
|---|---|---|
| Initialise a repository | `git init` | Creates a new Git repository in the current directory. |
| Check status | `git status` | Displays the current state of the working directory and staging area. |
| Stage changes | `git add <file>` | Adds selected file changes to the staging area. |
| Commit changes | `git commit -m 'message'` | Records staged changes in the repository history. |
| View history | `git log --oneline` | Displays the commit history in a compact format. |
| Create a branch | `git branch <name>` | Creates a new branch. |
| List branches | `git branch` | Displays the local branches in the repository. |
| Switch branches | `git switch <name>` | Changes the current working branch. |
| Publish changes | `git push` | Sends local commits to the remote repository. |
| Retrieve remote changes | `git pull` | Fetches changes from the remote repository and integrates them into the current branch. |

## Conclusion

Through this mission, I learned how Git tracks changes and how GitHub supports collaboration. I understood the difference between staging and committing, and explored how branches and Pull Requests help developers work independently and review changes before merging them.

## Evidence / Files

- `mission-06-git-github/task.md`
- `mission-06-git-github/README.md`
- Root `README.md` with the My Learning section
- Git commit history
- `update-about` branch
- Pull Request on GitHub




