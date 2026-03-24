# Eyethu Pro Radio Studio — GitHub Pages

## Deploy Steps
1. Create a new GitHub repository (public or private).
2. Upload `index.html` and `.nojekyll` to the root of the `main` branch.
3. Go to **Settings → Pages → Branch: main → Folder: / (root)** → Save.
4. Your app will be live at: `https://<your-username>.github.io/<repo-name>/`

## Notes
- If deploying to a **project page** (not a user/org page), update the `<base href="/">` 
  in `index.html` to match your repo name, e.g. `<base href="/eyethu-radio/">`.
- The `.nojekyll` file prevents GitHub from processing the app with Jekyll.
- All data is stored in `localStorage` — no server needed.
