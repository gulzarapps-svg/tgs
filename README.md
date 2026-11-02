# TarotGulzarSingh.com — Starter Website

This is a static HTML starter for Cloudflare Pages.

## Files
- `index.html` — homepage, services and enquiry section
- `blog.html` — blog landing page
- `privacy.html` — privacy notice placeholder
- `styles.css` — responsive mystical indigo/gold theme
- `script.js` — mobile navigation and current year

## Before publishing
1. Replace `https://tally.so/r/REPLACE_ME` in `index.html` with your actual Tally form URL. The current form is only a placeholder and will not collect leads correctly.
2. Replace `91XXXXXXXXXX` with your WhatsApp number in international format (digits only).
3. Add your real biography, services, pricing (if applicable), profile photo and social links.
4. Write and publish a complete privacy notice before collecting personal data.
5. Check every link and test the site on mobile.

## Deploy using GitHub + Cloudflare Pages
1. Create a GitHub account and a new repository named `tarotgulzarsingh-site`.
2. Upload all files in this folder to the repository root (not inside an extra nested folder).
3. In Cloudflare Dashboard, open Workers & Pages → Create application → Pages → Connect to Git.
4. Authorize GitHub and select the repository.
5. Framework preset: None. Build command: leave blank or `exit 0`. Build output directory: `/` (if the dashboard requires a directory, use the repository root setting supported by the current UI).
6. Deploy. Test the generated `*.pages.dev` URL.
7. In the Pages project, open Custom domains → Set up a domain → enter `tarotgulzarsingh.com`.
8. Add the domain as a Cloudflare zone and follow the exact nameserver instructions shown by Cloudflare.
9. At GoDaddy, change nameservers only after reviewing/copying all existing DNS records, especially MX/TXT records if you later add email.
10. Add `www.tarotgulzarsingh.com` as an additional custom domain and configure the preferred redirect/canonical domain.

Do not share passwords, OTPs, API keys or account recovery codes in chat.
