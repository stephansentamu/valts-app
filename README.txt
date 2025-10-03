Valts Starter Pack - quick instructions
Files included:
  - index.html    => simple coming-soon landing page. Replace 'yourdomain.com' with your real domain and update social links.
  - robots.txt    => allow all crawlers and reference sitemap.xml
  - sitemap.xml   => basic sitemap containing root URL. Update as you add pages.
  - README.txt    => this file.

How to use (fastest path if you don't have hosting):
1) Create a free GitHub account (github.com) and create a new repo named 'valts-landing' (public).
2) Upload the index.html, robots.txt, sitemap.xml to the repo (Use 'Add file' -> 'Upload files').
3) Go to GitHub Settings -> Pages -> Choose branch 'main' and folder '/ (root)' -> Save. GitHub will give you a github.io URL.
4) In your registrar (where you bought the domain), add a CNAME or ALIAS record pointing your domain to the GitHub Pages target (or follow Netlify instructions below to use Netlify instead).
   - If you prefer Netlify (recommended for easiest custom domain setup and automatic HTTPS):
     a) Create a free Netlify account (netlify.com).
     b) Click 'Add new site' -> 'Import from Git provider' -> connect GitHub -> select your repo.
     c) Deploy site (default settings are fine).
     d) In site dashboard -> Domain management -> Add custom domain -> enter your domain -> follow verification steps.
5) After your site is live at https://yourdomain.com, follow the Search Console and Bing verification steps below to verify ownership and submit sitemap.

DNS TXT verification (Google Search Console):
 - Use the 'Domain' property option in Search Console. It will give you a TXT record value like: google-site-verification=xxxxxxxx
 - Add that TXT record in your DNS provider (Cloudflare / Namecheap / GoDaddy / etc). It does not require the site to be live; only DNS control is needed.
 - Wait a few minutes, then click Verify in Search Console.

Bing + IndexNow:
 - Add your site to Bing Webmaster Tools (bing.com/webmasters) and verify ownership (DNS TXT or other methods).
 - In Bing WMT, enable IndexNow and follow instructions to host the key file or use the API to submit URLs.

Replace placeholders:
 - 'yourdomain.com' => replace with your real domain in every file.
 - 'yourhandle' => replace social URLs in index.html JSON-LD.

If you'd like, I can:
 - Replace 'yourdomain.com' and handles now (paste your domain and social handles), and regenerate the files for you.
 - Or, walk you through DNS TXT steps for Cloudflare/Namecheap/GoDaddy specifically — tell me your registrar name.
