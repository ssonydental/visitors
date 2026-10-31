# Visitors page (emergency dentist for visitors to New York)

Landing page for Smile Services of New York aimed at out-of-town visitors.

## Deploy with GitHub Pages
1. Create a new repo (e.g. `ssonydental/visitors`) and upload every file in this folder to the root (keep the `assets/` folder and `.nojekyll`).
2. Settings > Pages > Source: Deploy from a branch > `main` / `/ (root)` > Save.
3. The page will be live at `https://ssonydental.github.io/visitors/` until a custom domain is set.

## When the URL is decided
No `CNAME` file is included yet. Once the subdomain is chosen:
1. Add a file named `CNAME` containing only the domain (e.g. `visitors.ssonydental.com`).
2. In DNS, add a CNAME record: `<subdomain>` -> `ssonydental.github.io`.
3. Settings > Pages > Custom domain: enter the domain, then tick Enforce HTTPS once the certificate is issued.
4. If the domain is not `visitors.ssonydental.com`, find-and-replace that placeholder in `index.html` (canonical, og:url, JSON-LD), `robots.txt` and `sitemap.xml`.

## Still to fill in (search index.html for "fill in")
- Privacy Policy URL
- Google Business Profile URL (sameAs)
- Verify drive times / distances in the Getting Here section
