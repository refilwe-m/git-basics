# Git & GitHub Cheatsheet for Beginners  

This cheatsheet covers the most basic Git and GitHub commands to help you get started with version control.  


## **Basic Git Commands**  

### **Initialize a Repository**  
```bash
git init  
```
Initializes a new Git repository in your project folder.  

[Insert Screenshot: VS Code Source Tree after `git init`]  

---  

### **Check Repository Status**  
```bash
git status  
```
Shows the current state of your working directory (untracked, modified, or staged files).  

[Insert Screenshot: VS Code Source Tree with `git status` output]  

---  

### **Stage Changes**  
```bash
git add <file>      # Stage a specific file  
git add .           # Stage all changes  
```
Prepares changes to be committed.  

[Insert Screenshot: VS Code Source Tree after `git add .`]  

---  

### **Commit Changes**  
```bash
git commit -m "Your commit message"  
```
Saves staged changes with a descriptive message.  

[Insert Screenshot: VS Code Source Tree after commit]  

---  

### **View Commit History**  
```bash
git log  
```
Displays a log of all commits.  

[Insert Screenshot: VS Code Source Tree with `git log` output]  

---  

## **Working with GitHub**  

### **Clone a Repository**  
```bash
git clone <repository-url>  
```
Downloads a remote repository to your local machine.  

[Insert Screenshot: VS Code Source Tree after cloning]  

---  

### **Connect Local to Remote**  
```bash
git remote add origin <repository-url>  
```
Links your local repository to a remote GitHub repository.  

---  

### **Push Changes to GitHub**  
```bash
git push -u origin main  
```
Uploads local commits to the remote repository.  

[Insert Screenshot: VS Code Source Tree after `git push`]  

---  

### **Pull Changes from GitHub**  
```bash
git pull origin main  
```
Downloads the latest changes from the remote repository.  

[Insert Screenshot: VS Code Source Tree after `git pull`]  

---  

## **Branching Basics**  

### **Create a New Branch**  
```bash
git branch <branch-name>  
```
Creates a new branch.  

---  

### **Switch to a Branch**  
```bash
git checkout <branch-name>  
```
Moves to the specified branch.  

[Insert Screenshot: VS Code Source Tree showing branch switch]  

---  

### **Merge a Branch**  
```bash
git merge <branch-name>  
```
Combines changes from the specified branch into the current branch.  

---  

## **Handy Shortcuts**  
- `git diff` → Shows unstaged changes  
- `git reset <file>` → Unstage a file  
- `git restore <file>` → Discard local changes  

---  

### **Need Help?**  
- `git --help` → General Git help  
- `git <command> --help` → Help for a specific command  

---  

[Add any additional screenshots or notes as needed]  

---  
