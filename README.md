# Forest Program Inc. (Linghang Mentorship / 领航计划) — Public Organization Page

Static, public-facing website (no login wall) designed for **Forest Program Inc.** (California 501(c)(3) nonprofit organization, EIN `99-1905606`), fulfilling Stripe account activation and website verification requirements.

## Structure

- `index.html` — Organization overview, programs, transparent USD pricing table, legal entity details, and customer support contact information.
- `refund.html` — Standalone Refund & Cancellation Policy (linked in footer).
- `privacy.html` — Standalone Privacy Policy (linked in footer).
- `terms.html` — Standalone Terms of Service (linked in footer).
- `styles.css` — Responsive stylesheet matching the Overture / 领航校友会 visual design tokens.
- `assets/lh-web-logo.png` — Organization emblem.
- `vercel.json` — Clean URL routing for static hosting on Vercel.

## Pre-Submission Checklist (Stripe)

Before deploying and submitting the URL to Stripe:

1. **Contact Email**: Confirm `linghangeast@gmail.com` is actively monitored (or replace with your official `@linghangmentorship.org` / `@linghangmentorship.com` support email across all 4 HTML files).
2. **Optional Mailing Address / Phone**: If Stripe requests a physical mailing address on the site matching your IRS determination letter or bank statement, add it to the `#contact` section and `<footer>` in `index.html` (and the footers of `refund.html`, `privacy.html`, `terms.html`).
3. **Stripe Dashboard Alignment**:
   - **Legal Business Name**: `Forest Program Inc.` (exact match to IRS letter)
   - **DBA / Doing Business As**: `Linghang Mentorship` (or `The Lighthouse Mentorship Program`)
   - **Product Description**: Match the mentorship cohort fees, event tickets, and donations listed on `index.html`.

## Local Preview

```sh
python3 -m http.server 8080
```

Open `http://localhost:8080/`.

## Deployment

Deploy directly as a static site (no build step required):

- **Vercel**: Connect this repository or run `vercel --prod` (leave Build Command empty / Framework Preset: Other).
- **Cloudflare Pages / Netlify / GitHub Pages**: Serve the repository root directly.
