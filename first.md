# Introduction to Version Control & Git

**Name:** Amar Jadhav  
**Assignment:** Git Setup with a Reading Log  
**Branch:** `feature/reading-log-assignment`

## 1. Introduction

This project is created as part of the Introduction to Version Control & Git assignment.

The objective is to understand Git fundamentals, initialize a repository, track file changes, create meaningful commits, work with branches, and push the project to GitHub.

## 2. Git Configuration

Git was installed and configured globally using the following commands:

```bash
git config --global user.name "Amar Jadhav"
git config --global user.email "amar.jadhav@example.com"
```

Verify configuration:

```bash
git config --global --list
```

## 3. Books I Plan to Read

| No. | Book Name | Author | Status |
|---|---|---|---|
| 1 | Atomic Habits | James Clear | Reading |
| 2 | The Psychology of Money | Morgan Housel | Planned |
| 3 | Deep Work | Cal Newport | Planned |

## 4. Reading Log Updates

### Update 1: Atomic Habits

- Book: Atomic Habits
- Author: James Clear
- Status: Reading
- Added the first book to my reading list.

### Update 2: The Psychology of Money

- Book: The Psychology of Money
- Author: Morgan Housel
- Status: Planned
- Added the second book to my reading list.

### Update 3: Deep Work

- Book: Deep Work
- Author: Cal Newport
- Status: Planned
- Added the third book to my reading list.

## 5. Git Commands Practiced

| Git Command | Purpose |
|---|---|
| `git init` | Initialize a new Git repository |
| `git config --global` | Configure Git username and email |
| `git add` | Stage changes |
| `git commit` | Save changes in Git history |
| `git branch` | View and manage branches |
| `git switch -c` | Create and switch to a new branch |
| `git log --oneline` | View commit history |
| `git status` | Check working tree status |
| `git push` | Push commits to GitHub |

## 6. Commit History

The following three commits were created for the reading log:

1. `docs: add Atomic Habits to reading log`
2. `docs: add Psychology of Money to reading log`
3. `docs: add Deep Work to reading log`

### Git Log Output

Paste the actual output of:

```bash
git log --oneline
```

### Git Status Output

Paste the actual output of:

```bash
git status
```

## 7. Branch Information

**Branch Name:** `feature/reading-log-assignment`

All assignment work was completed on the feature branch.

## 8. GitHub Submission

The assignment was prepared for submission to GitHub using:

```bash
git push -u origin feature/reading-log-assignment
```

## 9. Conclusion

Through this assignment, I learned how to initialize a Git repository, configure Git globally, track file changes, create meaningful commits, manage branches, inspect commit history, and push my work to GitHub.

This exercise helped me understand the importance of version control in collaborative software development.
