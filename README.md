How to delete branch locally and remotely?

// delete branch locally
git branch -d localBranchName

// delete branch remotely
git push origin --delete remoteBranchName
================================================
How to list tags?

general approach:
$ git tags

with -n to show message of the tag creation:
$ git tag -n

sorting with version:
$ git tag -l --sort=-version:refname
more info on : https://git-scm.com/docs/git-tag
