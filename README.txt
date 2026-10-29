RITESH RAJPOOT — PERSONAL PORTFOLIO
===================================

CONTENTS
- index.html: portfolio page
- style.css: responsive styling
- script.js: mobile navigation and current year
- robots.txt and sitemap.xml: basic search-engine discovery files

BEFORE DEPLOYING
1. Open index.html in VS Code.
2. Find every occurrence of:
   https://YOUR-PORTFOLIO-URL.vercel.app/
3. Replace it with your actual Vercel URL after first deployment.
   Example: https://ritesh-portfolio.vercel.app/
4. Put your current PDF resume in this folder and name it exactly:
   resume.pdf
5. Review every skill and project description. Keep only accurate details.
6. Save all files.

DEPLOY FREE WITH VERCEL + GITHUB
1. Sign in to https://github.com/ and create a new repository named:
   ritesh-personal-portfolio
2. Upload index.html, style.css, script.js, robots.txt, sitemap.xml,
   README.txt, and resume.pdf (if you want the resume publicly downloadable).
3. Sign in at https://vercel.com/ using GitHub.
4. Click Add New -> Project and import the repository.
5. For this plain static site, no build command is needed. Deploy it.
6. Copy the live .vercel.app URL.
7. Replace YOUR-PORTFOLIO-URL.vercel.app in index.html, robots.txt,
   and sitemap.xml with the actual deployed hostname. Commit the changes
   to GitHub; Vercel should redeploy automatically.

GOOGLE INDEXING
1. Open https://search.google.com/search-console/
2. Add property -> URL prefix.
3. Enter the exact live URL, e.g. https://ritesh-portfolio.vercel.app/
4. Complete one of Google's offered ownership verification methods.
   For a Vercel-hosted static site, HTML meta-tag verification is often
   straightforward: copy the exact tag Google gives you into the <head>
   section of index.html, save, commit, and wait for Vercel to redeploy.
5. Return to Search Console and click Verify.
6. Use URL Inspection at the top to inspect your homepage and click
   Request Indexing if offered.
7. Submit https://YOUR-ACTUAL-HOSTNAME/sitemap.xml in the Sitemaps section.

IMPORTANT
- A submission does not guarantee that Google will index or rank the site.
  Crawling may take days or weeks.
- Do not publish personal details you do not want publicly available.
- This is a static portfolio. It does not need MongoDB or a backend.
