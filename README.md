# BNS Connect LLC — Website

Marketing site for **BNS Connect LLC** — a Fort Lauderdale low‑voltage, fiber optic and structured cabling contractor.

- Production: https://www.bnsconnectllc.com/
- Hosted on **Vercel** (auto‑deploys from \`main\`)
- Tech: static HTML + Tailwind CDN, no build step
- Lang: EN / ES / RU (in‑browser switcher)

## Files

- \`index.html\` — single‑page site with all sections
- \`logo.png\` / \`logo.svg\` — brand assets
- \`sitemap.xml\`, \`robots.txt\` — SEO

## Quote form (TODO)

The contact form posts to **Web3Forms** (free, no backend). To enable it:

1. Go to https://web3forms.com/ and create a free access key for \`info@bnsconnectllc.com\`.
2. In \`index.html\`, find:
   \`\`\`html
   <input type="hidden" name="access_key" value="REPLACE_WITH_YOUR_WEB3FORMS_KEY" />
   \`\`\`
3. Paste the access key in place of \`REPLACE_WITH_YOUR_WEB3FORMS_KEY\`.

Until that is done, the site falls back to a \`mailto:\` so submissions still reach you.

## Roadmap

- [ ] Real Web3Forms key
- [ ] 6–10 photos of completed work → add Portfolio section
- [ ] Google Business Profile
- [ ] og‑image 1200x630 (cropped from logo)
- [ ] Customer testimonials
- [ ] Partner / GC logos strip
