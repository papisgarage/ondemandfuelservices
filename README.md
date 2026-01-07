# On Demand Fuel Services Website

Professional fuel delivery and tank rental services website for South Florida.

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the "+" icon in the top right → "New repository"
3. Name it: `ondemandfuelservices` (or any name you prefer)
4. Make it **Public** (required for free GitHub Pages)
5. **Don't** initialize with README, .gitignore, or license
6. Click "Create repository"

### Step 2: Initialize Git and Push

Open your terminal/command prompt in this folder and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Make your first commit
git commit -m "Initial commit - On Demand Fuel Services website"

# Add your GitHub repository (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/ondemandfuelservices.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

### Step 4: Access Your Website

Your website will be live at:
```
https://YOUR_USERNAME.github.io/ondemandfuelservices/
```

It may take a few minutes for the site to be available after enabling Pages.

## 📁 Project Structure

```
├── index.html          # Main homepage
├── contact.html        # Contact page
├── logo/              # Company logo
├── pictures/           # All images and photos
├── start-server.*     # Local development servers
└── README.md          # This file
```

## 🛠️ Local Development

To test the website locally, use one of these methods:

**Option 1: Python (Easiest)**
```bash
python start-server.py
```

**Option 2: Batch File (Windows)**
Double-click `start-server.bat`

**Option 3: Node.js**
```bash
node start-server.js
```

Then open: http://localhost:8000

## 📝 Notes

- All images are in the `pictures/` folder
- Logo is in the `logo/` folder
- The website uses Tailwind CSS via CDN (no build step needed)
- All pages are static HTML - perfect for GitHub Pages!

## 🔄 Updating the Website

After making changes:

```bash
git add .
git commit -m "Description of changes"
git push
```

GitHub Pages will automatically update your live site within a few minutes.

