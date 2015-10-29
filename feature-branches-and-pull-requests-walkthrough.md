
# Feature Branches and Pull Requests Walkthrough

Create a new branch.

```
git checkout -b {feature branch name}
```

Make a change.

Commit the change.

Get latest.

```
git pull origin develop
```

Push to server.

```
git push origin {feature branch name}
```

Create pull request.

Get feedback.

Merge and close the PR.

Delete the branch (be sure to switch branch and get latest changes).

```
git remote prune origin --dry-run
```
