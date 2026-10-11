# Basic Point — marketing site

Static single-page site for **basicpoint.app** (Basic Point Ltd, Cyprus, Reg. No. HE 499467).

- `index.html` — the whole site (self-contained: inline CSS + JS, IBM Plex via Google Fonts).
- `robots.txt`, `sitemap.xml` — SEO basics.

No build step. It is plain static HTML.

## Deploy (free) — recommended: Cloudflare Pages

1. Go to https://dash.cloudflare.com → **Workers & Pages** → **Create** → **Pages** → **Upload assets**.
2. Drag this folder in. Project name: `basicpoint`. Deploy.
3. **Custom domains** tab → add `basicpoint.app` and `www.basicpoint.app`.
   - If the domain's DNS is already on Cloudflare, it wires up automatically.
   - Otherwise move the domain's nameservers to Cloudflare (free) when prompted.
4. HTTPS is automatic.

### Alternative: Netlify
`app.netlify.com` → *Add new site* → *Deploy manually* → drag this folder → *Domain settings* → add `basicpoint.app` → follow DNS steps.

### Alternative: Vercel
`vercel.com/new` → import or drag → *Settings → Domains* → add `basicpoint.app`.

All three are free for this and give automatic HTTPS + global CDN.
