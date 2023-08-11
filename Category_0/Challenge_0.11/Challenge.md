# Challenge 0.11: Undoing Changes and Reverting Commits

## Challenge Description

In this challenge, you'll learn how to undo changes in a Git repository by reverting commits, resetting the branch to a previous state, and discarding changes selectively. You'll explore various techniques to correct mistakes and manage the project's history effectively.

## Challenge Tasks

1. Open your terminal and navigate to a directory with a Git repository.

2. Use the `git log` command to view the commit history of the repository. Identify a recent commit that you want to undo.

3. Revert a specific commit using the `git revert` command. For example, to revert the most recent commit:

   ```bash
   git revert HEAD
   ```

4. Confirm that the revert commit has been created, and observe the changes made by the revert operation.

5. Use the `git reset` command to reset the branch to a previous commit, effectively removing the most recent commit. For example:

   ```bash
   git reset HEAD~1
   ```

6. Observe that the reset action has removed the most recent commit from the branch. Confirm the changes with `git log`.

7. Discard changes selectively using the `git checkout` command. For example, to discard changes made to a specific file:

   ```bash
   git checkout filename
   ```

8. Use the git clean command to remove untracked files and directories from your working directory.

9. Reflect on the techniques you've learned for undoing changes and reverting commits in Git.

10. Optional: Experiment with other Git commands for undoing changes and explore more advanced scenarios.

## Additional Notes

- Reverting commits allows you to create new commits that undo the changes introduced by the original commit.

- Resetting a branch allows you to move the branch pointer to a specific commit, effectively removing subsequent commits.

- Discarding changes using git checkout and cleaning untracked files with git clean help you maintain a clean working directory.

- Don't forget to refer to the [Category 0: Fundamental Git Commands](../about_0.md) section for an overview of all the challenges in this category.

## Resources

[Git Documentation - git-revert](https://git-scm.com/docs/git-revert)
[Git Documentation - git-reset](https://git-scm.com/docs/git-reset)
[Git Documentation - git-checkout](https://git-scm.com/docs/git-checkout)
[Git Documentation - git-clean](https://git-scm.com/docs/git-clean)

## Challenge Submission

After completing the challenge, create a new directory inside the "Category_0.11" directory (if not already provided) with a name "Solution" (e.g., "[Solution.md](./Solution.md)"). Inside this directory, include your solution files, such as the Git commands you used and the final state of your Git repository.

You can then commit and push your changes to your fork of the repository. Feel free to open an issue if you have any questions or need assistance

← [Previous Challenge](../Challenge_0.10/Challenge.md) || [Index](../../README.md) || [Next Challenge →](../Challenge_0.12/Challenge.md)
