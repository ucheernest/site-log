# Site Log — Three-Bedroom Decoration

A daily site supervision log for the three-bedroom apartment internal
decoration project. Runs entirely in your browser — no server, no
database, nothing to install.

## How to host this on GitHub Pages

You'll need a free GitHub account (github.com) if you don't already have one.

1. **Create a new repository**
   - Go to github.com → click the **+** in the top right → **New repository**.
   - Name it something like `site-log` (any name works).
   - Set it to **Public** (GitHub Pages on a free account requires a public repo).
   - Click **Create repository**.

2. **Upload the file**
   - On your new repo's page, click **Add file → Upload files**.
   - Upload `index.html` (the file in this folder).
   - Scroll down and click **Commit changes**.

3. **Turn on GitHub Pages**
   - In your repo, go to **Settings → Pages** (left sidebar, under "Code and automation").
   - Under **Build and deployment → Source**, choose **Deploy from a branch**.
   - Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
   - Wait about a minute, then refresh the page — GitHub will show you the
     live link, something like:
     `https://<your-username>.github.io/site-log/`

4. **That's your link.** Bookmark it, and open it from the same browser/device
   each time so your entries stay put — see the note below.

## Important: where your data lives

This page saves entries in your browser's local storage — think of it as a
notebook that lives on one specific device, in one specific browser. That
means:

- Opening the link on your phone won't show entries you added on your laptop
  (and vice versa) — they're separate notebooks.
- Clearing your browser's site data/history for this page will erase entries.
- No one else can see or edit your entries just by having the link — but
  they also won't see the *same* entries you see, since it's local to each
  device.

If you later want everyone on the same device/network to see the same live
data (true shared hosting), that needs a small backend database behind it —
let me know if you want that built out next.

## Updating the site later

Any time you want to change the page itself (not the log entries — those you
edit right on the page), just upload a new version of `index.html` to the
same repo, overwriting the old one. GitHub Pages will update automatically.
