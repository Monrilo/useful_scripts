| **Category**         | **Command**                        | **Description**                                                                 |
|----------------------|------------------------------------|---------------------------------------------------------------------------------|
| **Setup**          | `git config --global user.name "Your Name"` | Set your Git username (global).                                                |
|                      | `git config --global user.email "you@example.com"` | Set your Git email (global).                                                   |
|                      | `git init`                         | Initialize a new Git repository.                                               |
| **Cloning & Remote** | `git clone <repo-url>`             | Clone a repository to your local machine.                                      |
|                      | `git remote add origin <url>`      | Add a remote repository.                                                       |
|                      | `git remote -v`                    | View configured remotes.                                                       |
| **Basic Workflow**  | `git status`                       | Show the working tree status.                                                  |
|                      | `git add <file>`                   | Stage a file for commit.                                                       |
|                      | `git add .`                        | Stage all changed files.                                                       |
|                      | `git commit -m "message"`          | Commit staged changes with a message.                                          |
|                      | `git push`                         | Push commits to the remote repository.                                         |
|                      | `git pull`                         | Pull latest changes from remote repository.                                    |
| **Branching**       | `git branch`                       | List branches.                                                                 |
|                      | `git branch <branch-name>`         | Create a new branch.                                                           |
|                      | `git checkout <branch-name>`       | Switch to another branch.                                                      |
|                      | `git checkout -b <branch-name>`    | Create and switch to a new branch.                                             |
|                      | `git merge <branch>`               | Merge a branch into the current branch.                                        |
|                      | `git branch -d <branch>`           | Delete a local branch.                                                         |
| **Stashing**        | `git stash`                        | Temporarily save changes.                                                      |
|                      | `git stash pop`                    | Reapply stashed changes.                                                       |
| **Logs & History**   | `git log`                          | View commit history.                                                           |
|                      | `git log --oneline`                | View concise commit history.                                                   |
|                      | `git diff`                         | Show file changes not yet staged.                                              |
|                      | `git diff --staged`                | Show changes between staged files and last commit.                             |
| **Undoing**         | `git restore <file>`              | Undo changes to a file (unstaged).                                             |
|                      | `git reset <file>`                 | Unstage a file.                                                                |
|                      | `git reset --hard`                 | Discard all changes in working directory.                                   |
| **Clean Up**        | `git clean -f`                     | Remove untracked files.                                                  |
|                      | `git gc`                           | Run garbage collection to optimize repo.                                       |
