# Gesso Verve website

One-page website for Gesso Verve (web design and development by Yahia Akl).

## Files
- `index.html`: the whole website (styles, scripts and images are inside it)
- `.nojekyll`: tells GitHub Pages to serve the file as-is

## Edit your details
Open `index.html`, find the `CONFIG` block near the bottom of the file, and edit:
- `EMAIL`, `PRICE`, `LOCATION`, `WEEKS`
- `BOOKING_URL`: paste a Cal.com or Calendly link to send every Book button there
- social links (`LINKEDIN_URL`, `INSTAGRAM_URL`, `PORTFOLIO_URL`)

Replace the demo testimonials, the "40+ projects" and "4.9/5" numbers before launch.

## Publish with GitHub Pages
1. Create a new repository on GitHub, for example `gesso-verve`.
2. Upload `index.html`, `.nojekyll` and `README.md` to the repository root.
3. Go to **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. After a minute your site is live at `https://YOUR-USERNAME.github.io/gesso-verve/`.

## Use your own domain
1. In **Settings > Pages > Custom domain**, enter your domain (for example `gessoverve.com`) and save. GitHub creates a `CNAME` file for you.
2. At your domain registrar, add these DNS records:
   - `A` records for `@` pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - a `CNAME` record for `www` pointing to `YOUR-USERNAME.github.io`
3. Tick **Enforce HTTPS** once it becomes available.
