Important terms and ideas:

1. Merge conflict: A merge conflict occurs when Git is unable to automatically merge changes from different branches due to conflicting changes made to the same file or files. It requires manual intervention to resolve the conflicts and determine which changes to keep.
2. Fast-forward merge: A type of merge that occurs when the branches being merged have a linear history and one branch is ahead of the other. Git can automatically apply the commits from the source branch onto the target branch without creating a new commit.
3. Recursive merge: A type of merge that occurs when the branches being merged have diverging commit histories and there are conflicting changes. Git uses a recursive strategy to merge the branches and create a new commit that combines the changes from both branches.
4. Merge conflict resolution: When a merge conflict occurs, it is up to the user to manually resolve the conflict by editing the conflicting files and choosing which changes to keep. Git marks the conflicting sections in the file and provides options to accept incoming changes, accept current changes, or manually edit the conflicts.
5. Committing the merge: After resolving the merge conflict, the changes need to be committed using `git add` to stage the resolved files and `git commit` to create a merge commit that combines the changes from both branches.

Code snippets:

1. Merging branches:
```bash
git merge <branch_name>
```
- Use `git merge` followed by the branch name to merge the specified branch into the current branch.

2. Resolving a merge conflict:
- When a merge conflict occurs, manually edit the conflicting file(s) to resolve the conflicts and choose the desired changes. Use a text editor or Git tools like VS Code's merge conflict resolution features to modify the file and remove the conflict markers.
- After resolving the conflicts, use `git add` to stage the resolved files.
- Commit the resolved merge using `git commit` with an appropriate message.

These code snippets demonstrate the concepts of merging branches in Git, including how merge conflicts can arise when conflicting changes occur and how to manually resolve the conflicts and commit the merged changes.

Note: The code snippets provided are examples and may need to be adapted based on your specific Git repository and branch names.