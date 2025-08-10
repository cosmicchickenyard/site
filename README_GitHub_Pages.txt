# Publish this folder on GitHub Pages (no code required)

## What you have here
- `index.html` — your one-page website
- Several `.odt` files — download buttons on the page link to these
- `CNAME_template.txt` — optional (for a custom domain later)

---

## Quick path (GitHub subdomain — totally free)
1) Go to https://github.com and sign in (or create an account).
2) Click the **+** (top-right) → **New repository**.
3) Name it anything (example: `cosmicchickenyard-site`). Keep it **Public**.
4) Click **Create repository**.
5) On the next screen, click **Upload files**. Drag *everything from this folder* into the browser (or click **choose your files**).
   - Make sure `index.html` is at the **top level** (not inside another folder).
6) Scroll down, click **Commit changes**.
7) Open the repo **Settings** → **Pages** (left sidebar).
8) Under **Build and deployment**, set **Source** = “Deploy from a branch”.
9) Set **Branch** = `main` and **Folder** = `/root`, then **Save**.
10) Wait ~30–60 seconds. A green box will show your site URL, like:
    `https://YOUR-USERNAME.github.io/cosmicchickenyard-site/`

That link is live and shareable. You’re done.

---

## Optional: Use your own domain later
1) In **Settings → Pages**, click **Custom domain**, type `www.yourdomain.com`, and **Save**.
2) At your domain registrar (where you bought the name), add a **CNAME** record:
   - **Host/Name:** `www`
   - **Value/Target:** `YOUR-USERNAME.github.io`
3) (Optional) Redirect the root domain to `www` (search “ALIAS/ANAME apex to GitHub Pages” for your registrar).

> Tip: If you prefer a file-based method, open `CNAME_template.txt`, put your domain name only (e.g., `www.yourdomain.com`), save it as **CNAME** (no extension), and upload it to the repo root. Then do step #2 above at your registrar.

---

## Troubleshooting
- If the page shows a 404, wait a minute and refresh — GitHub is still building.
- If links don’t download, make sure the `.odt` files sit next to `index.html` in the repo.
- If you change files, just upload again and **Commit** — Pages redeploys automatically.
- You can always roll back under the **Commits** tab.

## Need help?
Open an Issue in your repo and paste: “Please help enable GitHub Pages for this site.” Or ask the assistant who made this bundle to walk you through it.