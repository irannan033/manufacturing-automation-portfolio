# Manufacturing Excellence & Automation Portfolio

A responsive, static personal portfolio website for a robotics, industrial automation, and manufacturing excellence engineer. Built with plain HTML, CSS, and JavaScript—no build tools, frameworks, or package installation required.

## Live demo
After enabling GitHub Pages, the site can be published at:

`https://irannan033.github.io/manufacturing-automation-portfolio/`

> The URL will work after you create the repository with this exact name and enable Pages.

## What's included
- Responsive portfolio landing page
- About, skills, project summaries, experience, education, and contact sections
- Six project brief pages in Markdown
- Custom CSS illustrations made with HTML/CSS/SVG
- Mobile navigation and contact-button behavior
- No backend, API keys, database credentials, or build step

## Publish to GitHub

### Option A — Upload using GitHub website
1. Create a new public repository named `manufacturing-automation-portfolio`.
2. Keep it empty (do not add a README if you will upload this folder's README).
3. Choose **Add file → Upload files**.
4. Upload the contents of this folder, not the ZIP file itself.
5. Commit the files to the `main` branch.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select branch `main`, folder `/(root)`, then save.
9. Wait for the Pages deployment and open the URL shown in Settings → Pages.

### Option B — Git from VS Code / PowerShell
Open this folder in VS Code, then run:

```powershell
git init
git add .
git commit -m "Create engineering portfolio"
git branch -M main
git remote add origin https://github.com/irannan033/manufacturing-automation-portfolio.git
git push -u origin main
```

If Git asks who you are, configure your Git identity once:

```powershell
git config --global user.name "Your Name"
git config --global user.email "your-github-email@example.com"
```

Create the empty GitHub repository before running `git push`. If the remote repository already exists, do not run `git remote add origin` again; use `git remote -v` to check it.

## Personalize before publishing
Search `index.html` and replace:
- `YOUR_EMAIL@example.com` with your professional email address
- `https://www.linkedin.com/` with your actual LinkedIn profile URL
- Any job titles, dates, and project wording that do not precisely match your experience

Check all performance figures and remove anything that cannot be supported by an approved report. Use only photos, diagrams, or screenshots you own or have permission to publish. Do not publish employer-confidential details, factory layouts, internal system addresses, API keys, credentials, or supplier documents.

## Project documentation
- [AMR Material Movement](projects/amr-material-movement.md)
- [AMR Performance Dashboard](projects/amr-performance-dashboard.md)
- [Worker Capacity Analytics](projects/worker-capacity-analytics.md)
- [RFID Material Tracking](projects/rfid-material-tracking.md)
- [Factory Automation Concepts](projects/factory-automation-concepts.md)
- [Power System Modeling](projects/power-system-modeling.md)

## Tech stack
HTML5 · CSS3 · JavaScript · GitHub Pages

## License
MIT. See [LICENSE](LICENSE).
