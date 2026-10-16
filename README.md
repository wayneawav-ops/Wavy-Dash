# Wavy Command — Phase 1
Tasks, Eisenhower Matrix, goals, habits, and planning. Hosted using free GitHub Pages.

## Run
Node 22+: `npm ci`, then `npm run dev`. Production: `npm run build`.

## Deploy
Upload this folder's contents to the main branch of wayneawav-ops/Wavy-Dash, including .github/workflows/deploy.yml and package-lock.json. In repository Settings → Pages choose GitHub Actions as Source. The workflow builds and publishes https://wayneawav-ops.github.io/Wavy-Dash/ on each push to main; it can also be run manually under Actions. No user-provided secrets are required.

## Data
The default deployment saves data in this browser only. No login, server, or cross-device synchronization is configured. Clearing browser storage removes saved data. Avoid sensitive information on shared devices. Source code is public; personal entries are not committed.

Optional Supabase code and schema remain for future setup, but are not needed for this deployment. Never commit .env files, credentials, or service role keys. All VITE_ values are public in browser builds.

## Mobile
Open the deployed URL in Safari, then Share → Add to Home Screen. Internet is required; offline caching and push notifications are not implemented.
