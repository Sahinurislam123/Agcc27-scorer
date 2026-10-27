# AGCC Scorer — GitHub Pages Demo

A static, mobile-first cricket tournament scoring prototype. It runs without a database and saves demo data in the browser's `localStorage`.

## Test locally
Open `index.html` in a browser. For best results, use a simple local web server or GitHub Pages.

## GitHub Pages
1. Create a GitHub repository (e.g. `agcc-scorer`).
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Open the Pages URL after deployment finishes.

## Demo admin login
- Email: `admin@agcc.local`
- Password: `AGCC2026`

You can change these demo credentials under **Admin Panel → App Settings**. They are only local browser values and are NOT secure authentication.

## Included
- Public Home, recent matches, tournament details, teams, players, points table
- Demo admin login and dashboard
- Add/edit/remove teams and players
- Create/edit fixtures
- Toss choice and live scoring controls (runs, extras, wickets, undo)
- Scorecard and match summary
- Local JSON export/import backup

## Important limitations before public launch
- This is a prototype, not a production scoring system.
- All changes are stored only in the current browser. They do not sync across devices/users.
- LocalStorage demo login is not secure. Do not use real passwords or sensitive information.
- Scoring logic is intentionally basic; validate edge cases and tournament-specific rules before official use.
- A database and server-side authentication/authorization (e.g. Supabase with Row Level Security) are needed for secure admin editing and real-time public viewing.
