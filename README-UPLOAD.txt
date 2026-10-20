RUEL GRAFT — WEBSITE UPLOAD GUIDE

CONTENTS
index.html         Home page
styles.css         Responsive site styling
script.js          Mobile navigation and automatic copyright year
assets/            Artwork and favicon
robots.txt         Search engine crawl guidance
sitemap.xml        Site map

DEPLOYMENT OPTION A: EXISTING WEB HOST / cPanel
1. Back up your current graftr.me website before replacing anything.
2. Open your hosting File Manager and locate the domain's document root (often public_html, but it may differ).
3. Upload the CONTENTS of this folder (not the enclosing graftr-site folder) to the document root.
4. Ensure index.html sits at the document root beside styles.css and script.js.
5. If an old index.php takes precedence, rename or archive it only after backing up.
6. Open https://graftr.me in an incognito window and test mobile navigation, images and email link.

DEPLOYMENT OPTION B: NETLIFY
1. Sign into Netlify and deploy the unzipped site folder using manual deploy.
2. Verify the temporary Netlify URL.
3. Add graftr.me as a custom domain and follow Netlify's displayed DNS instructions at your registrar.
4. Wait for DNS and SSL provisioning before considering the migration complete.

DEPLOYMENT OPTION C: VERCEL
1. Upload the folder to a Git repository.
2. Import it in Vercel as a static project; no build command is needed.
3. Add graftr.me in the project's domain settings and follow Vercel's DNS records.

EDITING
- Update wording and email links in index.html.
- Change colors and layout in styles.css.
- Replace images in assets while retaining filenames, or update the paths in index.html.
- The contact button opens the visitor's email app; this site does NOT collect form submissions.
- The artwork is an exploratory AI-generated concept, not a production-ready font or fully standardized script.
- Google Fonts are loaded online; visitors without connectivity will see fallback fonts.

BEFORE LAUNCH
- Confirm you control graftr.me hosting/DNS and preserve existing email records if changing DNS.
- Review text, image crops, and alt text.
- Test in Chrome, Safari, and on a phone.
- This is a static site: no database, shop, checkout, or custom calligraphy generator is included.
