# Muhammad — Cloud & DevOps Portfolio

A responsive, lightweight portfolio built with semantic HTML, CSS, and vanilla JavaScript. It is ready for GitHub Pages and does not require a build step.

## Files

- `index.html` — page content and structure
- `styles.css` — responsive layout, theme styles, and animations
- `script.js` — mobile navigation, light/dark theme toggle, and footer year
- `assets/Muhammad-Resume.pdf` — downloadable resume

## Preview locally

Open `index.html` in a browser. For a local web server, run this from the project directory:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

### Option A — user/organization site

1. Create a repository named exactly `muhammad21236.github.io` (replace the username if needed).
2. Extract this project and place `index.html`, `styles.css`, `script.js`, and the `assets` folder in the repository root.
3. Commit and push the files to the `main` branch.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select **main** and **/(root)**, then save.
7. Wait for GitHub Pages to publish the site. It will be available at `https://muhammad21236.github.io`.

### Option B — existing repository project site

1. Push these files to the root of an existing repository.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/(root)`, then save.
4. The site URL will be `https://muhammad21236.github.io/REPOSITORY-NAME/`.

## Customize before publishing

- Confirm the email address and LinkedIn URL in `index.html`.
- Replace `assets/Muhammad-Resume.pdf` if you update your resume.
- Project cards are intentionally limited to the three projects specified.
- The "Show More Projects" link opens the GitHub profile in a new tab.

## Push from PowerShell

Run these commands from inside the extracted project folder (after creating the GitHub repository):

```powershell
git init
git add .
git commit -m "Add cloud and DevOps portfolio"
git branch -M main
git remote add origin https://github.com/muhammad21236/muhammad21236.github.io.git
git push -u origin main
```

If the remote repository already exists locally, use `git remote set-url origin <repository-url>` instead of adding another remote.
