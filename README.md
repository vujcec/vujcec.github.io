# Weather conditions on web site (IP-based)

A zero-backend weather page that embeds **wttr.in**.  
No keys, no tracking. **wttr.in** auto-detects the visitor's location by their IP address.

---

 ![Dublin, IE (EU) example](/screenshots/Dublin-IE-EU-example.png)  ✈︎  ![Chicago, IL (US) example](/screenshots/Chicago-IL-US-example.png) 

---

## Quick start

1. Create a **new public repository**  
   (or private if your plan supports Pages for private repos).
2. Add these files:
   - `index.html`
   - `.github/workflows/deploy.yml`
3. Commit to `main` and push.
4. Go to **Settings > Pages** and ensure **Source** is set to **GitHub Actions**.

After the workflow finishes, your site will be live at:

```text
https://vujcec.github.io/
