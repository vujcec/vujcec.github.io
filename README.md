## Local weather conditions on GitHub Pages

A zero-backend weather page that embeds **wttr.in**.
No keys, no tracking. **wttr.in** auto-detects the visitor's location by IP address.

---

![Dublin, IE (EU) example](/screenshots/Dublin-IE-EU-example.png) ✈︎ ![Chicago, IL (US) example](/screenshots/Chicago-IL-US-example.png)

---

## Quick start

1. Create a **new public repository**
   (or private if your plan supports Pages for private repositories).
2. Add these files:
   - `index.html`
   - `.github/workflows/static.yml`
3. Commit to `main` and push.
4. Go to **Settings > Pages** and ensure **Source** is set to **GitHub Actions**.

After the workflow finishes, the site will be live at:

`https://<your-github-username>.github.io/`

## Notes

- The current weather is embedded from `https://wttr.in/?format=3`.
- IP-based location can be inaccurate when visitors use VPNs, mobile carriers, or some proxy networks.
- The page is intentionally simple and does not require JavaScript.
