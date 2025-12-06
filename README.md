# Weather conditions on web site (IP-based)

A zero-backend weather page that embeds **wttr.in**.  
No keys, no tracking. **wttr.in** auto-detects the visitor's location by their IP address.

---

## Examples

<table>
  <tr>
    <td align="center">
      <img src="/screenshots/Dublin-IE-EU-example.png" alt="Dublin, IE (EU) example" />
      <br />
      <sub>Dublin, IE (EU)</sub>
    </td>
    <td align="center" width="80">
      <h1>✈︎</h1>
    </td>
    <td align="center">
      <img src="/screenshots/Chicago-IL-US-example.png" alt="Chicago, IL (US) example" />
      <br />
      <sub>Chicago, IL (US)</sub>
    </td>
  </tr>
</table>

---

## Quick start

1. Create a **new public repository**  
   (or private if your plan supports Pages for private repos).
2. Add these files:
   - `index.html`
   - `.github/workflows/deploy.yml`
3. Commit to `main` and push.
4. Go to **Settings → Pages** and ensure **Source** is set to **GitHub Actions**.

After the workflow finishes, your site will be live at:

```text
https://vujcec.github.io/
