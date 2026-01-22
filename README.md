# Git commands with Explanation

```
1.git config --global user.name <user name>

2. git config --global user.email <email>
```
### Explanation : These commands make sure your user name and the email that you gave on creating git hub account, this is one time process it gives path to git where to push all the files.

```
3. git init
```
### Explanation : Initializes a new Git repository in the current directory. Creates a hidden .git folder to track changes.

```
4. git add <File name>

5. git add .
```
### Explanation : Stages changes for commit. Use git add . to stage all changes and add the file in staging area from current area

```
6. git commit -m <messege>
```
### Explanation : Saves staged changes into the repository history with a descriptive message.

```
7. git remote add origin <URL>

8. git push -u origin master
```
### Explanation : This command links your local Git repository to a remote repository. After running it, you can push (git push origin main) or pull (git pull origin main) changes between your local repo and the remote one. Without this, Git doesn’t know where to send or fetch code from.

```
9. git branch

10. git branch <branch name>

11. git checkout -b <branch name>

12. git branch -d <branch name>

13. git branch -D <branch name>
```
### Explanation : first command lists all the branches second one will create a new branch and if we use third command then it will create as well as use that branch. the fourth command will delete the branch but only after merging but if we want to delete that branch without merge then use the last command using -D.

```
14. git status -s
```
### Explanation :  Shows the state of your current area and staging area. - Uses short, symbolic indicators instead of long sentences. Helps to see which files are staged,modified or untracked Left side shows Staging area and Rigt side shows the Current area

```
15. git remote -v
```
### Explanation : This command manages the list of remote repositories linked to your local Git project.

```
16. git log 

17. git log --oneline
```
### Explanationm : first command shows the commit history of your repository and second will show a simplified or compact view of the commit history

```
18. git restore --staged <file name>

         OR

19. git restore --staged .
```
### Explanation : first command will revert back your file from staging area to current area and the second will revert back your all the files from staging to current area

```
20. git revert <commit Id>
# use latest commit id
```
### Explanation : this command will revert back the file from commit area to the current area

```
21. git reset --hard <commit id>
# use commit id upto which version you want to keep changes
```
### Explanation : when this command we use all staged changes will be cleared

```
22. git reset --soft <commit id>
```
### Explanation : when we use this command it remains all the staged changes means ready to commit. it undoes commits but keeps your changes staged, so you can recommit them.













