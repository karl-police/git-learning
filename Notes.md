# Rebase to update from origin
Rebasing is seems to be an alternative way to merging.


# Differences between branches

``git diff`` can generate a ``.patch`` file

```
git diff origin
```
By using this, it gets the differences between your current branch and the main branch for instance.

``git diff testing1..testing2`` gets the differences between these two specific branches.
Now, note when using ``git apply`` that it can fail, if it's not properly comparing the changes.
