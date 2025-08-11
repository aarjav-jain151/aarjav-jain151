# Task 5 - Deploy a Static Website Using GitHub Pages

## 📌 Objective
Host a simple static website for free using **GitHub Pages**.

---

## 🛠 Tools & Technologies Used
- HTML5
- CSS3
- Git & GitHub
- GitHub Pages

---

## 📂 Project Structure
```
static-site-T5/
│── index.html
│── style.css
│── images/
│ └── hero.jpeg
│── screenshots/
│ └── responsive-preview.png
└── README.md
```
---

## 🚀 Deployment Steps
1. Created a GitHub repository named **`static-site-T5`**.
2. Added all static website files (HTML, CSS, images).
3. Committed and pushed files to GitHub.
4. Enabled GitHub Pages from repository **Settings → Pages** (branch: `main`, folder: `/root`).
5. Waited for deployment to finish (takes 1–2 min).
6. Website is now live at: **https://aarjav-jain151.github.io/static-site-T5/**

---

## 📸 Preview
![Responsive Website Preview](screenshots/responsive-preview.png)

---

## 📱 How to Update
1. Make changes to local files.
2. Commit and push:
   ```bash
   git add .
   git commit -m "Update site"
   git push origin main
---

## **Step 3 – GitHub repo create karna**
- GitHub pe jao → **New Repository**.
- **Repo Name:** `static-site-T5`  
- **Description:** `Task 5 - Deploy a Static Website Using GitHub Pages`  
- Public repo create kar.
- **DO NOT** tick “Add README” — kyunki hum local se push karenge.

---

## **Step 4 – Local se Git initialize karke push**
```bash
cd ~/Desktop/static-site-T5

git init
git remote add origin https://github.com/aarjav-jain151/static-site-T5.git
git add .
git commit -m "Task 5 - Deploy static website using GitHub Pages"
git branch -M main
git push -u origin main
