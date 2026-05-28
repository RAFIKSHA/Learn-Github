# 🚀 Complete Step-by-Step Guide to Upload a VS Code Project to GitHub Using Git

---

# ✅ 1. Install Git

Download Git from the official website:

https://git-scm.com/downloads

After installation, check Git version:

```sh
git --version
```

If a version number appears, Git is installed successfully.

---

# ✅ 2. Configure Git (First-Time Setup)

Set your GitHub username and email:

```sh
git config --global user.name "Rafik Shah"
git config --global user.email "rafik2272@gmail.com"
```

Check configuration:

```sh
git config --list
```

---

# ✅ 3. Create a Project Folder

Create a new folder on Desktop:

```sh
mkdir Netflix-Clone
```

Move into the folder:

```sh
cd Netflix-Clone
```

Open the folder in VS Code:

```sh
code .
```

---

# ✅ 4. Create an HTML File

Inside VS Code, create a file named:

```text
index.html
```

Add this code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Clone</title>
</head>
<body>

    <h1>Hello Netflix Clone</h1>

</body>
</html>
```

Save the file.

---

# ✅ 5. Initialize Git

Open terminal in VS Code and run:

```sh
git init
```

This command converts the folder into a Git repository.

---

# ✅ 6. Check Git Status

```sh
git status
```

You will see:

```text
Untracked files:
index.html
```

---

# ✅ 7. Add Files to Git

```sh
git add .
```

This stages all files.

---

# ✅ 8. Commit the Project

```sh
git commit -m "Initial commit"
```

This saves the project version locally.

---

# ✅ 9. Create GitHub Repository

Open GitHub:

https://github.com/new

Repository name example:

```text
Netflix-Clone
```

Important:

* Do NOT add README
* Do NOT add .gitignore
* Keep repository empty

Click:

```text
Create Repository
```

---

# ✅ 10. Connect Local Project to GitHub

Copy your repository URL.

Example:

```text
https://github.com/RAFIKSHA/Netflix-Clone.git
```

Run:

```sh
git remote add origin https://github.com/RAFIKSHA/Netflix-Clone.git
```

---

# ✅ 11. Create Main Branch

```sh
git branch -M main
```

---

# ✅ 12. Upload Project to GitHub

```sh
git push -u origin main
```

Your project is now uploaded to GitHub successfully.

---

# ✅ 13. Future Updates Workflow

Whenever you modify the project:

## Check status

```sh
git status
```

## Add changes

```sh
git add .
```

## Commit changes

```sh
git commit -m "Updated project"
```

## Push updates

```sh
git push
```

---

# ✅ 14. Download Latest GitHub Changes

```sh
git pull origin main
```

---

# ✅ 15. Check Connected GitHub Repository

```sh
git remote -v
```

---

# ✅ 16. Remove Existing Remote

```sh
git remote remove origin
```

---

# ✅ 17. Common Git Commands

| Command            | Purpose              |
| ------------------ | -------------------- |
| git init           | Initialize Git       |
| git add .          | Add files            |
| git commit         | Save changes         |
| git push           | Upload code          |
| git pull           | Download latest code |
| git status         | Check status         |
| git remote -v      | Check connected repo |
| git branch -M main | Rename branch        |

---

# 🎯 Final Workflow Summary

```sh
git init
git add .
git commit -m "Initial commit"
git remote add origin YOUR_GITHUB_REPO_URL
git branch -M main
git push -u origin main
```

---

# 🚀 Congratulations

You have successfully:

* Created a project
* Initialized Git
* Connected GitHub
* Uploaded code to GitHub
* Learned daily Git workflow
