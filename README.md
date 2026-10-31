# travel.ssonydental.com (emergency dentist for visitors to New York)

Landing page for Smile Services of New York aimed at out-of-town visitors.

## Deploy with GitHub Pages
1. Create a new repo (e.g. `ssonydental/ssny-visitors`) and upload every file in this folder to the root (keep the `assets/` folder and `.nojekyll`).
2. Settings > Pages > Source: Deploy from a branch > `main` / `/ (root)` > Save.
3. The page will be live at `https://ssonydental.github.io/ssny-visitors/` until a custom domain is set.

## Custom domain: travel.ssonydental.com
1. The `CNAME` file in this folder already contains `travel.ssonydental.com`.
2. In DNS, add a CNAME record: `travel` -> `ssonydental.github.io`.
3. Settings > Pages > Custom domain: `travel.ssonydental.com`, then tick Enforce HTTPS once the certificate is issued.

## Still to fill in (search index.html for "fill in")
- Privacy Policy URL
- Google Business Profile URL (sameAs)
- Verify drive times / distances in the Getting Here section
