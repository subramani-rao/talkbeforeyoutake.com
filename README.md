# TalkBeforeYouTake.com premium acquisition site

A static, mobile-responsive domain acquisition website designed for GitHub Pages.

## Publish with GitHub Pages

1. Create a new public GitHub repository, for example `talkbeforeyoutake-com`.
2. Upload all files from this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. In **Custom domain**, enter `talkbeforeyoutake.com`.
7. Enable **Enforce HTTPS** once available.

## IONOS DNS

Keep the IONOS nameservers and add these records in the DNS area:

- A record for `@` → `185.199.108.153`
- A record for `@` → `185.199.109.153`
- A record for `@` → `185.199.110.153`
- A record for `@` → `185.199.111.153`
- CNAME for `www` → `<your-github-username>.github.io`

Remove conflicting A, AAAA or forwarding records for the root domain before connecting GitHub Pages.

## Search indexing

After the HTTPS website is live:

- Add the domain to Google Search Console and Bing Webmaster Tools.
- Submit `https://talkbeforeyoutake.com/sitemap.xml`.
- Confirm `https://talkbeforeyoutake.com/robots.txt` loads successfully.

## Contact

The enquiry form prepares an email to `suburao909@gmail.com`. No server or form-processing service is required, and visitor information is not stored by the site.
