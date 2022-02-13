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
![image](https://user-images.githubusercontent.com/99536233/153750790-ee9dc626-dbcd-4ece-9cbf-86c03305a5aa.png)
copy paste
![zeus](https://user-images.githubusercontent.com/99536233/153750499-7dd46405-7bfe-44dd-99b1-b4e2d1f4ea0b.png)
generated from Issue
![ullr](https://user-images.githubusercontent.com/99536233/153750640-d918c05a-035a-499f-83d4-e72e95507763.png)

