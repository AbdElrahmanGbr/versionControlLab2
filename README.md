**Lab 2**
How to delete branch locally and remotely?
```
// delete branch locally
git branch -d localBranchName

// delete branch remotely
git push origin --delete remoteBranchName
```
How to list tags?
```
general approach:
$ git tags

with -n to show message of the tag creation:
$ git tag -n

sorting with version:
$ git tag -l --sort=-version:refname
```
**more info on : _https://git-scm.com/docs/git-tag_**

How to delete tags locally and remotely?
```
locally :
git tag -d v1.8

remotely:
git push origin --delete v1.8
```
How to add Images to README.md?
```
You can display an image by adding ! and wrapping the alt text in [ ]. Then wrap the link for the image in parentheses ().\
![zeus](C:\Users\Administrator\Desktop\versionControlLab2\zeus.png)

```
![zeus](C:\Users\Administrator\Desktop\versionControlLab2\zeus.png)

