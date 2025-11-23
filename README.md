# Allplan Manual Graph

This repository hosts an interactive graph visualization using vis-network.

## Hosting on GitHub Pages

### Step-by-Step Setup:

1. **Create a GitHub repository**:
   - Go to https://github.com/new
   - Name it (e.g., `allplan-manual-graph`)
   - Make it **public** (required for free GitHub Pages)
   - Don't initialize with README (we already have one)
   - Click "Create repository"

2. **Push your files to GitHub**:
   ```bash
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```
   *(Replace YOUR_USERNAME and YOUR_REPO_NAME with your actual GitHub username and repository name)*

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click **Settings** (top menu bar)
   - Click **Pages** (in the left sidebar)
   - Under "Source", select **Deploy from a branch**
   - Choose **main** branch and **/ (root)** folder
   - Click **Save**

4. **Access your site**:
   - Wait 1-2 minutes for GitHub to build your site
   - Your site will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/home.html`
   - **Tip**: If you rename `home.html` to `index.html`, it will be accessible at the root: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### Important Note:

The HTML file references `lib/bindings/utils.js` which doesn't exist in this repository. You have two options:

1. **If the script is not essential**: Comment out line 5 in your HTML file:
   ```html
   <!-- <script src="lib/bindings/utils.js"></script> -->
   ```

2. **If the script is needed**: Add the `lib/bindings/utils.js` file to your repository before pushing.

### Troubleshooting:

- If your site shows a 404, wait a few minutes and refresh
- Make sure your repository is **public** (not private)
- Check that GitHub Pages is enabled in Settings → Pages

