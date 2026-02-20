# GitHub Pages Deployment Guide

This portfolio website is ready for deployment to GitHub Pages. Follow the steps below to get your site live.

## Prerequisites

- A GitHub account
- Git installed on your machine
- This repository

## Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com)
2. Click the **+** icon in the top right and select **New repository**
3. **IMPORTANT**: Name your repository as **`yourusername.github.io`** (replace `yourusername` with your actual GitHub username)
   - For example: `praneetha.github.io`
4. Set the repository to **Public** (required for free GitHub Pages)
5. Click **Create repository**

## Step 2: Configure Your Repository

1. Go to your repository settings
2. Navigate to **Settings** → **Pages**
3. Under "Build and deployment":
   - **Source**: Select "GitHub Actions"
   - The deployment workflow will automatically run on push

## Step 3: Initialize and Push Your Code

Open a terminal/PowerShell in your project directory and run:

```bash
# Initialize git repository (if not already initialized)
git init

# Add GitHub remote (replace with your repository URL)
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Rename branch to main (if needed)
git branch -M main

# Add all files
git add .

# Commit changes
git commit -m "Initial portfolio website commit"

# Push to GitHub
git push -u origin main
```

## Step 4: Monitor Deployment

1. Go to your repository on GitHub
2. Click the **Actions** tab
3. Watch the "Deploy to GitHub Pages" workflow
4. Once the workflow completes (shows green checkmark), your site is live!

## Step 5: Access Your Site

Your portfolio will be available at:
```
https://yourusername.github.io
```

For example, if your GitHub username is `praneetha`, your site will be at:
```
https://praneetha.github.io
```

## Step 6: Optional - Update Site URL in Config

To fully enable SEO features, update the `_config.yml` file:

```yaml
url: "https://yourusername.github.io"
baseurl: ""
```

## File Structure

```
yourusername.github.io/
├── index.html              # Main entry point
├── styles.css              # Stylesheet
├── script.js               # JavaScript functionality
├── README.md               # Project documentation
├── _config.yml             # Jekyll configuration
├── .gitignore              # Git ignore rules
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions workflow
├── images/                 # Image assets
│   └── praneetha.jpg
└── DEPLOYMENT_GUIDE.md     # This file
```

## Troubleshooting

### Site Not Showing Up
- Verify repository name is exactly `yourusername.github.io`
- Check that repository is **Public**
- Wait 1-2 minutes after first push
- Check GitHub Actions tab for deployment errors

### Images Not Loading
- Ensure image paths use relative URLs (e.g., `images/praneetha.jpg`)
- Check that image files exist in the images folder
- Clear browser cache and refresh

### Custom Domain (Optional)
If you want to use a custom domain:
1. In repository Settings → Pages
2. Add your custom domain in the "Custom domain" field
3. Update DNS records with your domain provider
4. GitHub will auto-generate an HTTPS certificate

## Updates and Maintenance

To update your portfolio after deployment:

```bash
# Make your changes to files
# Then:
git add .
git commit -m "Update portfolio with new projects"
git push
```

The GitHub Actions workflow will automatically rebuild and deploy your changes within 1-2 minutes.

## Resources

- [GitHub Pages Documentation](https://pages.github.com)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Jekyll Documentation](https://jekyllrb.com)

## Support

For issues or questions:
- Check GitHub Pages [troubleshooting guide](https://docs.github.com/en/pages/getting-started-with-github-pages/troubleshooting-publication-of-your-github-pages-site)
- Review GitHub Actions logs in the Actions tab
- Check repository Settings → Pages for status
