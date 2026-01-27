# 🚀 GitHub Pages Deployment - Step by Step

Your Git repository is ready! Follow these steps to deploy your website:

## ✅ Step 1: Create GitHub Repository

1. Go to **https://github.com** and sign in (or create an account)
2. Click the **"+"** icon in the top right → **"New repository"**
3. Fill in:
   - **Repository name**: `personal-website` (or any name you like)
   - **Description**: "My Personal Portfolio Website" (optional)
   - **Visibility**: Select **"Public"** (required for free GitHub Pages)
   - **DO NOT** check "Initialize with README" (we already have files)
4. Click **"Create repository"**

---

## ✅ Step 2: Connect and Push Your Code

After creating the repository, GitHub will show you commands. **But use these instead** (already prepared for you):

Open **PowerShell** in your `Personal Website` folder and run:

```powershell
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

**Replace:**
- `YOUR_USERNAME` with your GitHub username
- `YOUR_REPO_NAME` with the repository name you created (e.g., `personal-website`)

**Example:**
```powershell
git remote add origin https://github.com/Aneenaanu321/personal-website.git
git push -u origin main
```

**Note:** If you're asked for credentials:
- Username: Your GitHub username
- Password: Use a **Personal Access Token** (not your GitHub password)
  - Get token: GitHub → Settings → Developer settings → Personal access tokens → Generate new token
  - Select scope: `repo` (full control of private repositories)

---

## ✅ Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click the **"Settings"** tab (top menu)
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**:
   - Select: **Branch: `main`**
   - Select: **Folder: `/ (root)`**
5. Click **"Save"**

---

## ✅ Step 4: Your Website is Live! 🎉

- **Wait 1-2 minutes** for GitHub to build your site
- Your website will be live at:
  ```
  https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
  ```
  
**Example:**
```
https://Aneenaanu321.github.io/personal-website/
```

---

## 🔄 Updating Your Website

Whenever you make changes:

```powershell
git add .
git commit -m "Update website"
git push
```

GitHub Pages will automatically update in 1-2 minutes!

---

## 🎨 Custom Domain (Optional)

If you have a custom domain:

1. In GitHub Pages settings, add your domain
2. Follow GitHub's DNS instructions
3. Wait for DNS propagation (up to 48 hours)

---

## ❓ Troubleshooting

**Problem:** "Repository not found"
- **Solution:** Check your username and repository name are correct

**Problem:** "Authentication failed"
- **Solution:** Use Personal Access Token instead of password

**Problem:** Website shows 404
- **Solution:** Wait 2-3 minutes, then refresh. Make sure repository is Public.

**Problem:** Changes not showing
- **Solution:** Clear browser cache (Ctrl + F5) or wait a few minutes

---

## 📝 Quick Reference Commands

```powershell
# Navigate to your project
cd "c:\Users\Aneena\Desktop\Personal Website"

# Check status
git status

# Add changes
git add .

# Commit changes
git commit -m "Your commit message"

# Push to GitHub
git push

# View your repository
git remote -v
```

---

**Your website will be live in minutes! 🚀**
