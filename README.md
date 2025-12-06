# Weather conditions on web site (IP‑based)


A zero‑backend weather page that embeds **wttr.in**. No keys, no tracking. wttr.in auto‑detects the visitor's location by their IP address.


## Quick start


1. Create a **new public repository** (or private if your plan supports Pages for private repos, e.g. https://vujcec.github.io).
2. Add these files:
- `index.html`
- `.github/workflows/deploy.yml`
3. Commit to `main` and push.
4. In **Settings > Pages**, ensure *Source* is **GitHub Actions** (the default for this workflow). After the workflow finishes, your site will be live at:
`https://<your-username>.github.io/<repo-name>/`


## Custom domain (optional)


Create a `CNAME` file at the repo root with your domain.
