# Read Advisory Co — Client Pages

Live referral and trust pages for Read Advisory Co clients.  
Base URL: `https://readadvisoryco.github.io/Clients/`

---

## Active Client Pages

| Client | File | Live URL | Custom Domain | Status |
|--------|------|----------|---------------|--------|
| Charles Floeckher | `index.html` | [View Page](https://readadvisoryco.github.io/Clients/) | — | ✅ Live |
| Mike Case | `mike-case-referrals.html` | [View Page](https://readadvisoryco.github.io/Clients/mike-case-referrals.html) | — | ✅ Live |

---

## How to Add a New Client Page

1. Get the final HTML file from deliverables
2. Name it `firstname-lastname.html` (e.g. `sarah-johnson.html`)
3. Go to **Code** tab → **Add file** → **Upload files**
4. Upload the file and click **Commit changes**
5. Page is live at `https://readadvisoryco.github.io/Clients/firstname-lastname.html`
6. Add a row to the table above and commit the README update

---

## How to Add a Custom Domain to a Client Page

When a client is ready for their own URL (e.g. `referrals.mikecaseadvisory.com`):

1. Client adds a **CNAME record** in their domain DNS settings:
   - **Type:** CNAME
   - **Name:** referrals (or whatever subdomain)
   - **Value:** `readadvisoryco.github.io`
2. Go to **Settings → Pages** in this repo
3. Under **Custom domain** enter the full subdomain (e.g. `referrals.mikecaseadvisory.com`)
4. Check **Enforce HTTPS**
5. Update the Custom Domain column in the table above
6. DNS can take up to 24 hours to propagate

---

## File Naming Convention

```
firstname-lastname.html
```
Examples: `mike-case-referrals.html`, `charles-floeckher.html`

---

## Notes

- All pages are hosted via GitHub Pages on the `main` branch
- `index.html` is the default page that loads when visiting the base URL
- Do not delete `index.html` — it is Charles Floeckher's page
- Each client page is fully self-contained — one HTML file, no dependencies
