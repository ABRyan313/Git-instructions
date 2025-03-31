
Follow these steps to move your Java programs to your existing GitHub repository:

### 1. Open Terminal or Command Prompt  
Navigate to your Java exercise workspace folder:
```sh
cd /path/to/your/workspace
```

### 2. Initialize Git (If Not Already Initialized)  
Check if the folder is a Git repository:
```sh
git status
```
- If it's not a repository, initialize it:
  ```sh
  git init
  ```

### 3. Add Your GitHub Repository as Remote  
If you haven’t already linked your local folder to your GitHub repo, add it as a remote:
```sh
git remote add origin https://github.com/your-username/your-repository.git
```
(Check if it's already linked using `git remote -v`.)

### 4. Add and Commit Files  
```sh
git add .
git commit -m "Added Java exercise programs"
```

### 5. Push to GitHub  
If your GitHub repository is empty, push with:
```sh
git branch -M main
git push -u origin main
```
If your repo already has files, pull the latest changes first:
```sh
git pull origin main --rebase
git push origin main
```

After this, your Java programs should be available in your GitHub repository. 🚀
