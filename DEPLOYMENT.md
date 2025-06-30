# Deployment Guide

## Setting up Git and GitHub

### 1. Configure Git (First time only)

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### 2. Initialize Git Repository (Already done)

```bash
git init
git add .
git commit -m "Initial portfolio website commit"
```

### 3. Create GitHub Repository

1. Go to [GitHub.com](https://github.com)
2. Click the "+" icon in the top right
3. Select "New repository"
4. Name it "portfolio" or "my-portfolio"
5. Make it public
6. Don't initialize with README (we already have one)
7. Click "Create repository"

### 4. Connect Local Repository to GitHub

After creating the repository, GitHub will show you commands. Use these:

```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual GitHub username and repository name.

### 5. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" section
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch
6. Click "Save"
7. Your portfolio will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

## Local Development

### Start Local Server

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have it installed)
npx serve .
```

Then open your browser and go to: `http://localhost:8000`

### Stop Local Server

Press `Ctrl + C` in the terminal where the server is running.

## Updating Your Portfolio

After making changes to your files:

```bash
git add .
git commit -m "Update portfolio content"
git push
```

## Customization Checklist

Before deploying, make sure to update:

- [ ] Your name throughout the website
- [ ] Profile photo (add `profile-photo.jpg`)
- [ ] Contact information (email, phone, location)
- [ ] Social media links
- [ ] Skills section with your actual skills
- [ ] Projects with your real projects
- [ ] Work experience with your actual experience
- [ ] Education with your real education
- [ ] About section with your personal information

## Troubleshooting

### Git Issues

If you get permission errors:
```bash
git remote set-url origin https://YOUR_USERNAME@github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
```

### GitHub Pages Not Working

1. Check if the repository is public
2. Wait a few minutes for changes to propagate
3. Check the "Actions" tab for any deployment errors
4. Make sure the main branch is selected in Pages settings

### Local Server Issues

If port 8000 is busy:
```bash
python3 -m http.server 8080
```

Then use `http://localhost:8080`

## Next Steps

1. **Customize Content**: Update all placeholder content with your information
2. **Add Images**: Add your profile photo and project screenshots
3. **Test Responsiveness**: Check how it looks on mobile devices
4. **SEO Optimization**: Add meta tags and descriptions
5. **Analytics**: Add Google Analytics if desired
6. **Domain**: Consider buying a custom domain for your portfolio

## Useful Commands

```bash
# Check Git status
git status

# See commit history
git log --oneline

# Pull latest changes (if working on multiple computers)
git pull

# Create a new branch for features
git checkout -b feature-name

# Switch back to main branch
git checkout main
```

## Support

If you encounter any issues:

1. Check the GitHub documentation
2. Search for solutions on Stack Overflow
3. Check the browser console for JavaScript errors
4. Validate your HTML at validator.w3.org

---

**Your portfolio is now ready to showcase your work! 🎉** 