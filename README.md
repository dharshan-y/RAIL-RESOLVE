# RAIL//RESOLVE — File-by-file VS Code project

AI-enhanced railway passenger grievance redressal system demo.

## Files
- `index.html` — page structure and links to the CSS and JavaScript files.
- `style.css` — layout, colors, responsive design, and component styles.
- `app.js` — demo login, complaint reporting/classification, dashboards, routing, and localStorage persistence.
- `.gitignore` — excludes local/editor files and secrets.

## Run in VS Code
1. Extract this folder.
2. Open VS Code → **File → Open Folder** → select `RAIL-RESOLVE-FILE-BY-FILE`.
3. Install the **Live Server** extension if you do not already have it.
4. Right-click `index.html` → **Open with Live Server**. You can also open `index.html` directly in a browser.

## Demo login
Password for the built-in demo accounts: `Demo@123`
- `passenger@demo.com`
- `staff@demo.com`
- `admin@demo.com`

## GitHub upload using VS Code terminal
Create an empty repository named `RAIL-RESOLVE` on GitHub (do not initialize it with another README), then run these commands in the VS Code terminal from this folder:

```bash
git init
git add .
git commit -m "Add RAIL RESOLVE application files"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/RAIL-RESOLVE.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username. If `git remote add origin` says the remote already exists, run `git remote -v` to inspect it instead of adding it again.

## GitHub Pages
Repository → **Settings → Pages** → deploy from branch `main`, folder `/(root)` → **Save**.

## Important limitations
This is a front-end demo. It uses browser localStorage and rule-based classification, not a real AI service, secure server-side authentication, or shared production database. Do not use real passenger personal data or passwords.
