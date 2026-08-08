# namesakesite

Personal site for jasonmatthewhowes.com — plain static HTML/CSS, dark editorial style.

## Structure
- `index.html` — home
- `about.html` — bio
- `work.html` — projects / link-outs
- `contact.html` — contact info
- `css/style.css` — shared styles
- `CNAME` — custom domain for GitHub Pages

## To edit content
Open the HTML files and replace anything in `[PLACEHOLDER]` brackets or inside
`.placeholder` notice boxes — those mark spots meant for real copy and real links.

## Deploy (GitHub Pages)
1. Push to `main` (already set up).
2. In the GitHub repo: Settings → Pages → Source → Deploy from branch `main` / root.
3. Point your domain's DNS to GitHub Pages (A records to GitHub's IPs, or a CNAME to
   `jasonmatthewhowes.github.io` if using a subdomain) — GitHub's Pages docs have the
   current values.
4. Once DNS propagates, GitHub will serve the site at jasonmatthewhowes.com using the
   `CNAME` file already in this repo.
