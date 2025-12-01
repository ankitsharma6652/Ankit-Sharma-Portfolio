# 🚀 GitHub Pages Deployment Guide

## Step-by-Step Instructions to Deploy Your Portfolio

### Prerequisites
- GitHub account (create at github.com if you don't have one)
- Your portfolio files ready

---

## 📋 Method 1: Using GitHub Web Interface (Easiest)

### Step 1: Create Repository
1. Go to [github.com](https://github.com)
2. Click the **"+"** icon (top right) → **"New repository"**
3. Repository name: `portfolio` (or `your-username.github.io` for custom URL)
4. Description: "Professional Data Analyst Portfolio"
5. Set to **Public**
6. ✅ Check "Add a README file"
7. Click **"Create repository"**

### Step 2: Upload Files
1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop ALL these files:
   ```
   - index-v2.html
   - styles-v2.css
   - script-v2.js
   - index.html
   - styles.css
   - script.js
   - README.md
   ```
3. Scroll down, add commit message: "Initial portfolio upload"
4. Click **"Commit changes"**

### Step 3: Rename Main File
1. Click on `index-v2.html` in your repository
2. Click the **pencil icon** (Edit)
3. Change filename from `index-v2.html` to `index.html`
4. Scroll down, commit message: "Set V2 as main portfolio"
5. Click **"Commit changes"**
6. **IMPORTANT:** Also rename the old `index.html` to `index-v1.html` first!

### Step 4: Enable GitHub Pages
1. Go to repository **Settings** (gear icon)
2. Scroll down to **"Pages"** in left sidebar
3. Under "Source":
   - Branch: Select **"main"** (or **"master"**)
   - Folder: Select **"/ (root)"**
4. Click **"Save"**
5. Wait 2-3 minutes

### Step 5: Get Your URL
Your portfolio will be live at:
```
https://your-username.github.io/portfolio
```
Or if you named it `your-username.github.io`:
```
https://your-username.github.io
```

---

## 📋 Method 2: Using Git Command Line (Advanced)

### Step 1: Initialize Git
```bash
cd "/Users/ankit-sharma/Downloads/Ankit Sharma Portfolio"
git init
```

### Step 2: Rename Files
```bash
# Rename V2 to be the main portfolio
mv index.html index-v1.html
mv index-v2.html index.html
mv styles-v2.css styles.css
mv script-v2.js script.js
```

### Step 3: Add Files
```bash
git add .
git commit -m "Initial portfolio commit"
```

### Step 4: Create GitHub Repository
1. Go to github.com and create new repository named `portfolio`
2. Copy the repository URL

### Step 5: Push to GitHub
```bash
git remote add origin https://github.com/your-username/portfolio.git
git branch -M main
git push -u origin main
```

### Step 6: Enable Pages
Follow Step 4 from Method 1 above

---

## 🎨 After Deployment Checklist

### Test Your Live Site
- [ ] Visit your GitHub Pages URL
- [ ] Test all navigation links
- [ ] Check theme toggle (light/dark)
- [ ] Test feedback button (Gmail)
- [ ] Click all project links
- [ ] Test on mobile device
- [ ] Check LinkedIn/GitHub links

### Update Your Profiles
- [ ] Add portfolio URL to LinkedIn
- [ ] Add to resume
- [ ] Update email signature
- [ ] Share on social media

---

## 🔧 Troubleshooting

### Site Not Loading?
1. Wait 5 minutes (GitHub Pages takes time)
2. Check Settings → Pages for deployment status
3. Ensure branch is set to "main"
4. Clear browser cache (Cmd+Shift+R)

### CSS Not Loading?
1. Check file names match exactly
2. Ensure `styles.css` is in same folder as `index.html`
3. Check for typos in `<link>` tag

### 404 Error?
1. Ensure `index.html` exists (not `index-v2.html`)
2. Check repository is Public
3. Verify Pages is enabled in Settings

---

## 📊 Setting Up Google Analytics

### Step 1: Create GA Account
1. Go to [analytics.google.com](https://analytics.google.com)
2. Click "Start measuring"
3. Account name: "Portfolio"
4. Property name: "Ankit Sharma Portfolio"
5. Select "Web" platform
6. Enter your GitHub Pages URL

### Step 2: Get Tracking ID
1. Copy your **Measurement ID** (looks like: G-XXXXXXXXXX)
2. Open `index.html` in text editor
3. Find `YOUR_GA_ID` (appears twice)
4. Replace both with your actual ID

### Step 3: Verify
1. Save and push changes to GitHub
2. Visit your live site
3. Go back to Google Analytics
4. Check "Realtime" → Should see yourself!

---

## 🎯 Custom Domain (Optional)

### If You Buy a Domain (e.g., ankitsharma.com)

1. **In GitHub:**
   - Settings → Pages
   - Custom domain: `ankitsharma.com`
   - Save

2. **In Domain Registrar:**
   - Add A records:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```
   - Add CNAME: `www` → `your-username.github.io`

3. **Wait 24 hours** for DNS propagation

---

## 📱 Social Media Preview

### Add Open Graph Tags
Already included in your portfolio! When you share on LinkedIn/Twitter, it will show:
- Your name
- Portfolio description
- Professional preview

---

## 🔄 Updating Your Portfolio

### After Making Changes:

**Method 1 (Web):**
1. Go to your GitHub repository
2. Click on file to edit
3. Make changes
4. Commit
5. Wait 2-3 minutes for deployment

**Method 2 (Git):**
```bash
git add .
git commit -m "Update portfolio content"
git push
```

---

## 📈 Monitoring

### Track Your Portfolio Performance

**Google Analytics Dashboard:**
- Visitors per day
- Most viewed sections
- Geographic location
- Device types (mobile/desktop)
- Traffic sources

**GitHub Insights:**
- Repository → Insights
- See traffic and clones

---

## 🎉 Success Checklist

After deployment, you should have:
- ✅ Live portfolio at GitHub Pages URL
- ✅ Google Analytics tracking visitors
- ✅ README.md explaining your project
- ✅ Both V1 and V2 versions preserved
- ✅ All links working
- ✅ Mobile responsive
- ✅ Professional presentation

---

## 🆘 Need Help?

If you encounter issues:
1. Check GitHub Pages documentation
2. Verify all file names are correct
3. Ensure repository is Public
4. Wait a few minutes for changes to deploy
5. Clear browser cache

---

## 🚀 Quick Start Commands

```bash
# Navigate to portfolio folder
cd "/Users/ankit-sharma/Downloads/Ankit Sharma Portfolio"

# Rename V2 as main
mv index.html index-v1.html
mv index-v2.html index.html

# Initialize git
git init
git add .
git commit -m "Initial commit"

# Connect to GitHub (replace with your URL)
git remote add origin https://github.com/ankitsharma6652/portfolio.git
git branch -M main
git push -u origin main
```

Then enable Pages in GitHub Settings!

---

**Your portfolio will be live and professional! 🎉**

Good luck with your job search! 🚀
