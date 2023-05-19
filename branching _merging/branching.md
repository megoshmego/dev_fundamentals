Important terms and ideas:

1. Branching: The process of creating a divergent line of development in Git to work on separate features or changes without affecting the main codebase.
2. Default branch: The initial branch in a Git repository, commonly named "master," which is automatically created when initializing a new repository.
3. Branch: A parallel version of a repository that allows for independent development and experimentation.
4. Switching branches: Moving between different branches in a Git repository to work on different sets of changes.
5. Commit: A snapshot of changes made to the codebase at a specific point in time, recorded in the Git repository's history.

Code snippets:

1. Creating a new branch:
```bash
git branch <branch_name>
```
- Use `git branch` followed by a meaningful name to create a new branch.

2. Checking available branches:
```bash
git branch
```
- Use `git branch` to list all the branches in the repository, with the current branch indicated by an asterisk.

3. Switching to a branch:
```bash
git checkout <branch_name>
```
- Use `git checkout` followed by the branch name to switch to a different branch.

4. Making changes on a branch:
- Create, modify, or delete files as desired in the repository.
- Use `git add <file(s)>` to stage the changes for the next commit.
- Use `git commit -m "Commit message"` to create a new commit with the staged changes.

5. Checking commit history:
```bash
git log
```
- Use `git log` to view the commit history of the repository, showing the commits made on the current branch.

6. Switching back to the default branch:
```bash
git checkout master
```
- Use `git checkout` followed by the default branch name (e.g., "master") to switch back to the default branch.

These code snippets demonstrate the concepts of branching in Git, including creating a new branch, switching between branches, making changes on a branch, checking commit history, and switching back to the default branch.

Note: The code snippets provided are examples and may need to be adapted based on your specific Git repository and branch names.