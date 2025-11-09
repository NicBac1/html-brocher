# Social Identity and Advocacy

An interactive brochure and assessment tool for exploring social identity and advocacy concepts.

## Features

- 📚 Educational content on social identity and advocacy
- 🎮 Interactive Advocacy Readiness Assessment game
- 💬 Discussion questions for group engagement
- 📱 Responsive design for all devices

## Deployment to GitHub Pages

### Option 1: Deploy from main branch (Recommended)

1. **Create a GitHub repository:**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it anything you like (e.g., `social-identity-advocacy`)

2. **Initialize and push your code:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click on **Settings**
   - Scroll down to **Pages** in the left sidebar
   - Under **Source**, select **Deploy from a branch**
   - Choose **main** branch and **/ (root)** folder
   - Click **Save**

4. **Access your site:**
   - Your site will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`
   - It may take a few minutes to deploy

### Option 2: Deploy from gh-pages branch

If you prefer to keep your source code separate:

```bash
git checkout -b gh-pages
git push origin gh-pages
```

Then in Settings > Pages, select the `gh-pages` branch.

## Files

- `index.html` - Main HTML file (GitHub Pages looks for this)
- `image.png` - Header banner image
- `image copy.png` - Repeating background pattern
- `brocher.html` - Original file (kept for reference)

## Local Development

Simply open `index.html` in your web browser to view the site locally.

## License

This project is for educational purposes.

