# Git-and-Github-Workshop-DRESTEIN-24
NAME: Muthulakshmi D

REGISTER NUMBER :  212223040122

DEPARTMENT :  B.E CSE

YEAR :  II

## 1. Setup and Initialize:

What command do you use to create a new directory named `git-workshop` and navigate into it?

```
mkdir git-workshop
cd git-workshop
```
## 2. Initialize a Git Repository:

What command initializes a Git repository in your directory?
```
git init
```
## 3.Create and Modify Files:

How do you create a new file named hello.txt and add the content 'Hello, Git Workshop!' to it using a single command?
```
echo "Hello, Git Workshop!" > hello.txt
```
## 4. Check the Status of Your Repository:

What command displays the status of your repository?
```
git status
```
## 5. Stage and Commit Changes:

What command stages the file hello.txt?
```
git add hello.txt
```
What command commits the staged file with the message 'Add hello.txt with welcome message'?
```
git commit -m "Add hello.txt with welcome message"
```
## 6. Branching:

What command creates a new branch named update-content?
```
git branch update-content
```
How do you switch to the update-content branch?
```
git checkout update-content
```
## 7. Make Changes on the Branch:

What command would you use to append the text 'This is a simple Git assignment.' to hello.txt?
```
echo "This is a simple Git assignment." >> hello.txt
```
What command stages and commits the changes with the message 'Update hello.txt with additional message'?
```
git add hello.txt
git commit -m "Update hello.txt with additional message"
```
## 8. Merge Changes:

What command switches you back to the main branch?
```
git checkout main
```
How do you merge the update-content branch into main?
```
git merge update-content
```
## 9. View Commit History:

What command shows the commit history?
```
git log
```
## 10. Undo and Reset (Practice Safely):

If you make a change to hello.txt that you want to revert before committing, what command would you use?
```
git restore hello.txt
```
How can you reset your branch to a previous commit (optional, for advanced practice)?
```
git reset --hard
```
## 11. Push to a Remote Repository (Optional):

What command adds a remote repository named origin?
```
git remote add origin
```
What command pushes your local main branch to the remote repository?
```
git push origin main
```

# file
```
"C:\Users\HP\OneDrive\Documents\folder\certificates\documents\RECORD\git and github.pdf"
```
