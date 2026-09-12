NORTHMARK GARAGE DOOR — how to publish

1. Upload EVERYTHING in this folder to your host (Netlify, Vercel, cPanel, Hostinger, etc.).
   Easiest: netlify.com -> "Add new site" -> drag this whole folder. Done.

2. Domain: the files use https://northmarkgaragedoor.ca/ in canonical / sitemap / schema.
   If your real domain is different, search & replace that text in all files before uploading.

3. Clean URLs (/garage-door-repair-toronto without .html) are handled by:
   netlify.toml (Netlify), vercel.json (Vercel), .htaccess (Apache / cPanel).

4. After launch:
   - Google Search Console -> add property -> submit https://YOURDOMAIN/sitemap.xml
   - Google Business Profile -> same name + phone as the site (416-505-6228)
   - The callback form currently shows a thank-you only. To receive emails, connect it to a service like Formspree.
