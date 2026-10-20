# Spiritual Reboot website

One-page site for spiritualrebootcommunity.com, hosted on Netlify.

## Files

- `index.html`: the page
- `styles.css`: all styling
- `thanks.html`: shown after someone sends the prayer request form
- `images/banner.jpg`: channel banner (hero background and social share image)
- `images/profile.jpg`: channel profile picture (portrait and browser tab icon)

The `images` folder isn't included yet. Add the two channel images with exactly those file names before the first deploy.

## Deploying

1. Push this folder to a GitHub repo.
2. In Netlify: **Add new site → Import an existing project → GitHub**, then pick the repo.
3. Build command: leave empty. Publish directory: `.` (the repo root).
4. Deploy, then check the `*.netlify.app` address.
5. **Domain management → Add a domain** → `spiritualrebootcommunity.com`, then follow the DNS instructions.
6. In **Forms**, confirm `prayer-request` shows up after the first deploy, then set up an email notification to spiritualrebootcommunity@gmail.com.

## Notes

- The "Latest videos" section embeds the channel's uploads playlist, so it updates on its own whenever a new video goes up.
- Each production deploy uses Netlify credits on the free plan, so preview locally (open `index.html` in a browser) and push changes in batches.
