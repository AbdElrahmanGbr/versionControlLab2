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
1- simply copy paste of image into the edit README.md here
![zeus](https://user-images.githubusercontent.com/99536233/153750499-7dd46405-7bfe-44dd-99b1-b4e2d1f4ea0b.png)
2- opening issue and creating a new one, drag drop the image you want to upload and copy its link
```
![unknown_2022 02 13-13 22](https://user-images.githubusercontent.com/99536233/153750705-04966f05-7c5e-46e9-bb23-17567e0f2749.png)
![zeus](https://user-images.githubusercontent.com/99536233/153750499-7dd46405-7bfe-44dd-99b1-b4e2d1f4ea0b.png)
![ullr](https://github.com/AbdElrahmanGbr/versionControlLab2/issues/4#issue-1135685298.png)

