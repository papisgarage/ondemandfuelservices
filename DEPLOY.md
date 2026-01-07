# Quick GitHub Pages Deployment Guide

## Fast Setup (5 minutes)

### 1. Create GitHub Repository
- Go to github.com → New repository
- Name: `ondemandfuelservices`
- Make it **Public**
- Click "Create repository"

### 2. Upload Files via GitHub Web Interface
- In your new repository, click "uploading an existing file"
- Drag and drop all files from this folder
- Commit changes

### 3. Enable GitHub Pages
- Go to **Settings** → **Pages**
- Source: **main branch** → **/ (root)**
- Click **Save**

### 4. Your Site is Live!
- URL: `https://YOUR_USERNAME.github.io/ondemandfuelservices/`
- Wait 2-3 minutes for first deployment

## Using Git Command Line

If you prefer using Git:

```bash
# In this folder
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ondemandfuelservices.git
git push -u origin main
```

Then enable Pages in repository Settings → Pages.

## Custom Domain (Optional)

If you have a custom domain (like ondemandfuelservices.com):

1. In GitHub Pages settings, add your custom domain
2. Update DNS records with your domain provider:
   - Type: `CNAME`
   - Name: `@` or `www`
   - Value: `YOUR_USERNAME.github.io`

## Troubleshooting

- **Site not loading?** Wait 5-10 minutes after first deployment
- **Images not showing?** Check that all files in `pictures/` folder are uploaded
- **404 errors?** Make sure `index.html` is in the root folder

