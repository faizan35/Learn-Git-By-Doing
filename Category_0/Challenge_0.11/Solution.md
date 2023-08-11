# Challenge 0.11: Undoing Changes and Reverting Commits - Solution

In this solution, we'll explore techniques for undoing changes in a Git repository, including reverting commits, resetting branches, and discarding changes selectively.

### What is `git revert` ?

- The git revert command in Git is used to create a new commit that undoes the changes made in a previous commit.

## Solution Steps

### 1. Open your local reposiroty.

### 2. **View the Commit History**:

- Use the `git log` command to view the commit history of the repository.
- Identify a recent commit that you want to **undo**.

1. **Revert a Commit**: To revert a specific commit, use the `git revert` command. For example, to revert the most recent commit, you can use the following command:

   ```bash
   git revert HEAD
   ```
