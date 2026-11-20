Dream Lip Sync — landing, privacy policy and support pages (GitHub Pages: https://ilego.github.io/lipsyncsite/).

- `privacy.html` and `support.html` are the store-listing URLs: keep their paths.
- SEO: every page has description, canonical and Open Graph tags; `index.html` carries
  MobileApplication/FAQPage/HowTo JSON-LD, `support.html` a FAQPage matching the visible FAQ.
  Keep JSON-LD answers identical to the visible text and do not add store ratings.
- `sitemap.xml` lists the three pages; submit it in Google Search Console and Bing Webmaster
  Tools for the URL-prefix property `https://ilego.github.io/lipsyncsite/` (a project site cannot
  serve a root robots.txt).
- Google Play links carry `referrer=utm_source=lipsyncsite…` so installs from this site are
  attributed in Play Console / Firebase.
