# GitHub Pages Setup Guide — vandusensharene.github.io

Total time: about 10 minutes. No coding required.

## Step 1 — Create your GitHub account (3 min)

1. Go to **github.com** and click **Sign up**
2. Enter your email, create a password
3. When asked for a username, enter: **vandusensharene**
   - If it's taken, GitHub will tell you immediately — come back to Claude for a backup and we'll adjust the files
4. Verify your email when GitHub sends the confirmation

## Step 2 — Create the repository (2 min)

1. Once signed in, click the **+** icon (top right) → **New repository**
2. Repository name: **vandusensharene.github.io**
   - Must be exactly this — username + `.github.io` is what makes it a free website
3. Set it to **Public** (required for free GitHub Pages)
4. Do NOT check "Add a README" (we have our own)
5. Click **Create repository**

## Step 3 — Upload the files (3 min)

1. On the new empty repository page, click the link that says **"uploading an existing file"**
2. Unzip the package Claude gave you on your computer
3. **Before uploading:** put your dashboard file in place —
   - Find `capstone_skills_dashboard.html` (downloaded from Claude previously)
   - Rename it to `index.html`
   - Move it into the `projects/sales-booking-dashboard/` folder (a README in that folder has these same instructions)
4. Drag ALL the files and folders into the GitHub upload area
   - Important: drag the *contents* of the unzipped folder, not the outer folder itself
5. Scroll down, type a short message like "Initial portfolio upload," and click **Commit changes**

## Step 4 — Turn on GitHub Pages (2 min)

1. In your repository, click **Settings** (top menu)
2. In the left sidebar, click **Pages**
3. Under "Build and deployment" → Source: select **Deploy from a branch**
4. Branch: select **main** and folder **/ (root)**, then click **Save**
5. Wait 1–2 minutes, then visit: **https://vandusensharene.github.io**

Your portfolio is live.

## After it's live

- Add the URL to your LinkedIn (Featured section and/or Contact info)
- Add it to your resume header next to your LinkedIn link
- Include it in your capstone substitution materials for Springboard
- To add future projects: create a new folder under `projects/`, drop in an
  `index.html`, and ask Claude to update the homepage card for it

## Troubleshooting

- **404 error:** Wait 2–3 more minutes; first deploys can be slow. Confirm the repo name is exactly `vandusensharene.github.io` and Pages is enabled.
- **Homepage loads but dashboard link is broken:** The dashboard file isn't named `index.html` or isn't inside `projects/sales-booking-dashboard/`.
- **Username taken at signup:** Come back to Claude with your second choice — the files reference the username in a few places and need a quick find-and-replace.
