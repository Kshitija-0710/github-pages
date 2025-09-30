# 🌐 GitHub Pages Static Website - DevOps Learning Reference

## 📖 Project Overview

This project demonstrates how to **host a static website** (HTML + CSS) for free using **GitHub Pages**.
The site serves as a **reference for anyone learning DevOps**, providing a roadmap and an interactive suggestion form.

🔗 **Live Website:** [https://kshitija-0710.github.io/github-pages/](https://kshitija-0710.github.io/github-pages/)

---

## 📂 Project Structure

```bash
github-pages/
├── index.html           # Main homepage
├── style.css            # Custom styling
└── devops-roadmap.svg   # Timeline-style roadmap with tool icons
```

---

## 🧭 DevOps Learning Roadmap

This website provides a step-by-step guide for anyone who wants to start and grow in DevOps:

1. Linux Basics & Scripting
2. Git & GitHub for Version Control
3. Docker & Containerization
4. Kubernetes & Orchestration
5. CI/CD with Jenkins & GitHub Actions
6. Terraform & Infrastructure as Code
7. Monitoring & Logging (Prometheus, Grafana, Stackdriver)
8. Cloud Platforms (AWS & GCP)

---

## 📸 Visual Timeline

The roadmap is also represented as an interactive timeline with tool icons:

* Icons above the line represent each tool.
* Timeline dots connect to the labels below the line.
* Makes roadmap easier to visualize for beginners.

![DevOps Roadmap](devops-roadmap.svg)

---

## 💬 Share Your Suggestions

We welcome ideas, resources, and suggestions related to DevOps learning.
Please submit your feedback here: [Google Form](https://forms.gle/anoWE8frdUzarNfq8)

**Form description:**
*This form is for collecting ideas, resources, and suggestions related to the DevOps learning journey. Your feedback will help explore new tools, practices, and projects.*

---

## 🚀 Deployment Steps

### 1. Create Website Files

* `index.html` → homepage
* `style.css` → styles for the page

### 2. Push to GitHub

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/kshitija-0710/github-pages.git
git push -u origin main
```

### 3. Enable GitHub Pages

* Go to **Repo → Settings → Pages**
* Select **Branch: main** and **Folder: root**
* Save settings

### 4. Access Website

* Open the link provided by GitHub Pages
* Example: `https://kshitija-0710.github.io/github-pages/`

---

## 🎨 Customization

* Edit `index.html` to add new sections
* Update `style.css` for colors, fonts, and layouts
* Add more pages (e.g., `about.html`) and link them

---

## 📌 Interview Questions

**1. What is GitHub Pages?**
Free static site hosting service by GitHub.

**2. Can you host dynamic apps here?**
❌ No, only static content (HTML, CSS, JS).

**3. What are the limits of GitHub Pages?**

* Repo size ≤ 1 GB
* File size ≤ 100 MB
* 100 builds/hour

**4. How do you update the website?**
Push new commits to the repo → Pages auto-deploys.

**5. What happens when you delete the repo?**
The hosted site is removed.

**6. What is the default file that loads?**
`index.html`.

**7. Can you use a custom domain?**
✅ Yes, by configuring DNS and adding it in repo settings.

---

✨ This site is built as a reference for anyone learning DevOps and hosted for free using GitHub Pages.