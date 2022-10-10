## 1. Git status
```
git status
```
Example
![](./1.Git%20Status.PNG)

Shows information about the current changes ( new files added, updated, deleted, renamed etc)

## 2. Git Add
```
git add .
```
Adds all the current changes to the staging area.

```
git add <filename>
```
Adds the specic file to the staging area.
Example
![](./2.Git%20add.PNG)

## 3. Commit
```
git commit -m "Commit messege"
```
Example
![](./3.Git%20Commit.PNG)

Commits the changes

## 4. Push

```
git push origin main
```
Example
![](./4.Git%20Push.PNG)

Push the changes in the staging area to the remote main branch. We can replace the main branch with any other branch name.

## 5. Create new branch

```
git branch <new branch name>
```
Example
![](./5.Git%20create%20new%20branch.PNG)

Creates a new branch with given name.

## 6. List all branch on local

```
git branch
```
Example
![](./5.Git%20create%20new%20branch.PNG)

Lists all branch that are present on local repository.

## 7. Switch to new branch

```
git switch <branch name>
```
or
```
git checkout <branch name>
```
Example
![](./6.Git%20checkout.PNG)

Switch to the given branch name.

## 8. Fetch

```
git fetch
```
Example
![](./11.Git%20fetch.PNG)

Updates the repository by downloading the objects and refs.


## 9. Pull

```
git pull
```
Example
![](./8.Git%20pull.PNG)


## 10. Merge

```
git merge <branch name>
```
Example
![](./7.Git%20merge.PNG)

Merges changes in given branch to the current branch.
 

## 11. Delete branch

```
git branch -d <branch name>
```
Example
![](./9.Git%20delete%20branch.PNG)

delete branch

## 12. Log

```
git log
```
Example
![](./10.Git%20log.PNG)

Shows commit history of the repository

## 13. Git Clone
```
git clone <repository url>
```
Example
![](./12.Git%20clone.PNG)

Clones the repository to the local machine.
