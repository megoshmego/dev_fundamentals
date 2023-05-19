Important terms and ideas:

1. Creating a branch and switching simultaneously: Git provides a convenient way to create a new branch and switch to it at the same time using the `git checkout -b` command. By using this syntax, you can avoid the separate steps of creating a branch and then switching to it.

2. Basis for a new branch: The current branch you are on when creating a new branch serves as the basis for the new branch. The new branch will include all the commits and changes made on the current branch up to that point.

3. Switching branches: You can switch between branches using the `git checkout` command followed by the branch name. This allows you to work on different branches and access their respective commit history and file changes.

4. Git log: The `git log` command displays the commit history of the current branch, showing all the commits and their corresponding information in a concise format.

5. Deleting branches: Once a branch has been merged or is no longer needed, you can delete it using the `git branch -d <branch_name>` command. This removes the branch label and does not affect the commits or changes made on the branch.

Code snippets:

1. Creating a branch and switching to it:
```bash
git checkout -b <branch_name>
```
- Use `git checkout -b` followed by the branch name to create a new branch and switch to it in a single command.

2. Switching to an existing branch:
```bash
git checkout <branch_name>
```
- Use `git checkout` followed by the branch name to switch to an existing branch.

3. Deleting a branch:
```bash
git branch -d <branch_name>
```
- Use `git branch -d` followed by the branch name to delete a branch that has been merged into the main branch.

These code snippets demonstrate the concepts of creating branches, switching branches, and deleting branches in Git.