# Security Guard - GitHub Pages Deployment

This folder contains the built website files ready for GitHub Pages.

## How to deploy on GitHub Pages:

### Method 1 - Simple (Recommended):
1. Create a new GitHub repository named `security-guard`
2. Upload ALL files in this folder directly to the repo
3. Go to **Settings → Pages**
4. Set Source: **Deploy from a branch**
5. Set Branch: **main** → **/ (root)**
6. Click **Save**
7. Your site will be live at: `https://YOUR_USERNAME.github.io/security-guard/`

### Method 2 - Using Git:
```bash
cd security-guard-deploy
git init
git add .
git commit -m "Deploy Security Guard website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/security-guard.git
git push -u origin main
```
Then enable GitHub Pages from Settings → Pages.

## Files included:
- `index.html` - Main entry point
- `assets/` - CSS and JS bundles
