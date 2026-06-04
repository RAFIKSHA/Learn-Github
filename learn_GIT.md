### 🔹 **Step-by-Step Guide to Using Git with GitHub in VS Code**  

---

## ✅ **1. Install Git (If Not Installed)**
👉 Download and install **Git** from the official website:  
🔗 [Git Download](https://git-scm.com/downloads)  

👉 Check if Git is installed:  
```sh
git --version
```
If it shows a version number, Git is installed successfully.  

---

## ✅ **2. Configure Git (First-Time Setup)**
Run these commands to set up your Git username and email:  
```sh
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```
👉 **These details will be used in your commits.**  

---

## ✅ **3. Clone Your GitHub Repository**
Go to **your GitHub repository** and copy the **HTTPS URL**.  
🔗 Your repo: `https://github.com/RAFIKSHA/Web-development.git`  

Now, open **VS Code** and run:  
```sh
git clone https://github.com/RAFIKSHA/Web-development.git
```
👉 **This will download the repository to your local machine.**  

---

## ✅ **4. Open the Project in VS Code**
Navigate to the folder where the repo is cloned:  
```sh
cd Web-development
```
👉 Then, open it in **VS Code**:  
```sh
code .
```

---

## ✅ **5. Add a New File & Save Changes**
Create a new **HTML file** in VS Code (e.g., `index.html`).  

📌 Example content for `index.html`:  
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Git Page</title>
</head>
<body>
    <h1>Hello, GitHub!</h1>
</body>
</html>
```
👉 Save the file (`Ctrl + S` or `Cmd + S` on Mac).  

---

## ✅ **6. Check the Status of Changes**
Run this command to see which files were added or modified:  
```sh
git status
```
👉 You should see `index.html` as an **untracked file**.  

---

## ✅ **7. Add Files to Git**
Now, add the file to Git's tracking system:  
```sh
git add .
```
👉 This stages all new and modified files.  

---

## ✅ **8. Commit the Changes**
Create a commit message to save the changes locally:  
```sh
git commit -m "Added index.html"
```
👉 **Commits create a version history of your changes.**  

---

## ✅ **9. Push to GitHub**
Upload your changes to GitHub:  
```sh
git push origin main
```
👉 If your branch is different (e.g., `master`), use:  
```sh
git push origin master
```
✅ **Your changes should now be visible on GitHub!**  

---

## ✅ **10. Pull Latest Changes (If Needed)**
If you made changes on GitHub and want them locally:  
```sh
git pull origin main
```
👉 **This syncs your local repo with GitHub.**  

---

### 🎯 **Now You Have Successfully Set Up Git in VS Code!**  

