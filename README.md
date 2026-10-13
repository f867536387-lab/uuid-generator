# UUID Generator — free online UUID v4 tool site

A zero-dependency static site built by following CloudHu's outbound tutorial
(find keyword -> build site -> deploy -> domain -> search console).

## Deploy (tutorial step 3)
1. Push this folder to a GitHub repository.
2. Go to vercel.com -> New Project -> import the GitHub repo -> Deploy (no build settings needed).
3. You get a `*.vercel.app` URL that is publicly accessible.

## After deploy (steps 4-5)
- Optional: buy a domain on Spaceship, add it in Vercel, switch nameservers to Vercel DNS.
- Submit the domain + /sitemap.xml in Google Search Console and Bing Webmaster.
  For GSC TXT verification, add the TXT value and redeploy / push to GitHub.
