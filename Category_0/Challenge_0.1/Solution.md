# Challenge 0.1: Initializing a Git Repository - Solution

In this solution, we'll walk through the process of initializing a new Git repository from scratch and completing the tasks outlined in the challenge description.

## Solution Steps

1. **Create a New Directory:** We begin by creating a new directory on our local machine. You can use the following command to create a directory with your chosen name:

   ```bash
   mkdir my-git-project
   ```

2. **Initialize a Git Repository:** To initialize a new Git repository in the created directory, we use the `git init` command:
   ```bash
   cd my-git-project
   git init
   ```
3. **Add a New File:** For this example, let's create a simple text file named "hello.txt" using a text editor or command line. You can use the following command to create the file and add some content:

   ```bash
   echo "Hello, Git!" > hello.txt
   ```

4. **Check Repository Status:** To check the status of your Git repository and see the changes you've made, use the `git status` command:

   ```bash
   git status
   ```

   This will display information about untracked files, modified files, and the branch you're on.

5. **Stage Changes:** To stage the changes for the "hello.txt" file, use the `git add` command:

   ```bash
   git add hello.txt
   ```

6. **Commit Changes:** Now, let's commit our changes with a meaningful commit message using the `git commit` command:

   ```bash
   git commit -m "Initial commit: Add hello.txt"
   ```

   Your commit message should describe the purpose of the commit.

7. **View Commit History:** To view the commit history of your repository, use the **git log** command:
   ```bash
   git log
   ```
   This will display a list of commits, including the commit message, author, date, and commit hash.

## Conclusion

With these steps, you've successfully initialized a new Git repository, added a file, staged and committed changes, and viewed the commit history. You now have a basic understanding of how to start a new Git project and manage version control.
