# Coaching Classes — GitHub Pages Ready

This project is configured for **GitHub Pages**.

## Upload to GitHub

1. Create a new GitHub repository.
2. Upload **all files and folders from this ZIP** to the repository root.
3. Make sure the branch is named `main`.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, choose **GitHub Actions**.
6. Push to `main` (or use **Actions → Deploy to GitHub Pages → Run workflow**).
7. After the workflow finishes, GitHub will show the live Pages URL.

The Vite configuration uses relative asset paths (`base: './'`), so the site works correctly on a GitHub Pages project URL such as:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

No Node.js setup is needed on your computer for deployment; GitHub Actions installs dependencies and builds the site automatically.

## Local development

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

The generated production site is placed in `dist/`.
