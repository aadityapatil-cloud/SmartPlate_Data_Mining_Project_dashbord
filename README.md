# Smart Food Waste Management Dashboard

Single-file static dashboard (`index.html`), deployed on Render as a Static Site.

## Run locally
    python3 -m http.server 8000
Open http://localhost:8000

## Deploy on Render
1. Push this folder to a GitHub repo.
2. Render Dashboard -> New + -> Blueprint -> select the repo (uses `render.yaml`).
3. Click Apply. Your site goes live at https://smart-food-waste-dashboard.onrender.com

Manual alternative: New + -> Static Site -> Build Command: (empty) -> Publish Directory: `.`
