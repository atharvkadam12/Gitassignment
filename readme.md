# Upload Project to GitHub

steps to push this project folder to GitHub account.

## 1. Open Git Bash or Terminal
Navigate to the project folder:

```bash
cd path/to/Gitassignment
```

## 2. Initialize a Git Repository
```bash
git init
```

## 3. Check the Files
```bash
git status
```

## 4. Add Files to the Repository
```bash
git add .
```

## 5. Commit the Changes
```bash
git commit -m "Initial commit"
```

## 6. Create a Repository on GitHub
- Go to https://github.com
- Click the New button
- Give your repository a name
- Choose Public or Private
- Click Create repository

## 7. Connect Local Repo to GitHub
Replace YOUR_USERNAME and REPO_NAME with your actual GitHub username and repository name:

```bash
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
```

## 8. Push the Project to GitHub
```bash
git branch -M main
git push -u origin main
```

## 9. Future Updates
After making changes, use:

```bash
git add .
git commit -m "Your message"
git push
```
