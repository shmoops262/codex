# Codex Landing Page

This repository contains the Zantray VR startup landing page built for a Haitian venture.

## Getting Started

Open `index.html` in a modern browser to explore the experience. All assets are static, so no build tools are required.

## Publishing to GitHub

1. **Create a Git repository (if needed).**
   ```bash
   git init
   git add .
   git commit -m "Initial Zantray VR site"
   ```
2. **Create a repository on GitHub.** Use the GitHub UI to create a new repository under your account.
3. **Add the remote origin.** Replace `<USERNAME>` and `<REPO>` with your details.
   ```bash
   git remote add origin git@github.com:<USERNAME>/<REPO>.git
   ```
   If you prefer HTTPS:
   ```bash
   git remote add origin https://github.com/<USERNAME>/<REPO>.git
   ```
4. **Push the site.**
   ```bash
   git push -u origin main
   ```
   Use `master` instead of `main` if your repository uses that default branch.

## Deploying with GitHub Pages

1. Commit and push your changes to the default branch (`main` or `master`).
2. In the GitHub repository settings, enable **GitHub Pages** and choose the branch and `/ (root)` directory.
3. Your site will be available at `https://<USERNAME>.github.io/<REPO>/` after a short build period.

## License

MIT
