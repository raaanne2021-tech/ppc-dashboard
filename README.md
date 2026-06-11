# PPC Team Workspace

Internal workspace for Platinum Premier Construction.

## Files
- `index.html` — Login page
- `dashboard.html` — Daily tasks, priorities, notes
- `projects.html` — Project tracker
- `sops.html` — SOPs & Playbooks
- `links.html` — Quick links hub
- `style.css` — Shared styles

## Default Password
`PPC2026`

To change it: open `index.html`, find `const PASS = 'PPC2026'` and update.

## Deploy to GitHub Pages

1. Create a free GitHub account at github.com if you don't have one
2. Click **+ New repository** → name it `ppc-workspace` → set to **Public** → Create
3. Click **Add file → Upload files** → drag the entire `ppc-workspace` folder contents
4. Commit the files
5. Go to **Settings → Pages → Source → main branch → / (root)** → Save
6. Your site will be live at: `https://YOUR-USERNAME.github.io/ppc-workspace`

That's it! Share the URL + password with your team.

## Notes
- All task/project data is saved in the browser (localStorage) — each device stores its own data
- SOP cards link directly to your Notion pages
- The password is client-side only (good for internal use, not for sensitive data)
