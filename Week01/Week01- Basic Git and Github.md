
# 🌟 Week 01 - Basic Git and GitHub

Welcome to Week 01 of our Laravel Web Developer course!  
In this session, we’ll learn how to use Git and GitHub to manage code and collaborate with others.

---

## 🔍 1. Verify Git Version

Make sure Git is installed on your system:

```bash
git -v
```

You should see something like:

```
git version 2.XX.X
```

---

## 🛠️ 2. Initialize Git Repository

Inside your project folder, run:

```bash
git init
```

This will create a new Git repository in your project directory.

---

## 🖼️ 3. Add and Commit a File (e.g. `logo.jpg`)

Let’s add an image and make your first commit:

```bash
git add logo.jpg
git commit -m "SBKU Logo"
```

---

## 🌿 4. Rename the Default Branch to `main`

To follow modern naming conventions:

```bash
git branch -M main
```

---

## ☁️ 5. Connect to Remote Repository on GitHub

Replace the URL below with your actual GitHub repository URL:

```bash
git remote add origin https://github.com/itsanvert/test-git-github.git
```

You can check if the remote was added:

```bash
git remote -v
```

---

## 🚀 6. Push the First Commit to GitHub

Now push your local changes to GitHub:

```bash
git push -u origin main
```

---

## 📸 7. Add and Commit Remaining Files

To add all remaining files (e.g. cat and dog pictures):

```bash
git add .
git commit -m "Cat and Dog Picture"
```

---

## 📤 8. Push All Changes to GitHub

Finally, push all committed files:

```bash
git push origin main
```

---

## ✅ Summary

By now, you have:

- Initialized a Git repository ✅  
- Made your first commits ✅  
- Connected your project to GitHub ✅  
- Pushed your code to a remote repository ✅  

Keep practicing these commands. Git is an essential tool for every developer. 🚀

---
