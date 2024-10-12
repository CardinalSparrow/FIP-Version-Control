# FIP-Version-Control

## To create a new Git repository locally:
```bash
git init FIP-Version-Control
cd FIP-Version-Control
```

Link the local repository to a remote:
```bash
git remote add origin https://github.com/CardinalSparrow/FIP-Version-Control.git
```
## To clone an existing repository:
```bash
git clone https://github.com/CardinalSparrow/FIP-Version-Control.git
```

## To create a new branch:
```bash
git checkout -b new-branch
```

## To stage and commit changes:
```bash
git add .
git commit -m "Added new feature"
```

## To undo a commit while keeping the changes:
```bash
git revert <commit-hash>
```

## To completely remove the commit and changes:
```bash
git reset --hard <commit-hash>
```

## To pull changes from the remote repository:
```bash
git pull FIP-Version-Control main
```

## To push changes to the remote repository:
```bash
git push FIP-Version-Control feature-branch
```

## To fetch updates from the remote repository without merging:
```bash
git fetch FIP-Version-Control
```

## To merge `new-branch` into `main`:
```bash
git checkout main
git merge new-branch
```

## To rename the current branch:
```bash
git branch -m new-branch-name
```

## To revert pull requests
After pushing changes, create a pull request (PR) from the GitHub UI. You can review and merge the PR, or revert a merged PR using:
```bash
git revert -m 1 <commit-hash-of-PR-merge>
```
