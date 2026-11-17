# Forest Program Inc (Linghang Mentorship / Overture | 领航校友会) — Public Organization Page

Static, public-facing website (no login wall) for **Forest Program Inc** (U.S. 501(c)(3) nonprofit organization, EIN `83-4682819`), fulfilling Stripe account activation and website verification requirements.

## Structure

- `index.html` — Organization overview, Overture alumni annual membership ($120.00 USD/year), East Coast mentorship program fees ($300.00 USD cohort fee; free application), legal entity details, and customer support contact information.
- `refund.html` — Standalone Refund & Cancellation Policy (linked in footer).
- `privacy.html` — Standalone Privacy Policy (linked in footer).
- `terms.html` — Standalone Terms of Service (linked in footer).
- `styles.css` — Responsive stylesheet matching the Overture / 领航校友会 visual design tokens.
- `assets/lh-web-logo.png` — Organization emblem.
- `vercel.json` — Clean URL routing for static hosting on Vercel.

## Pre-Submission Checklist (Stripe)

Before submitting the deployed URL to Stripe:

1. **Contact Email**: Confirm `linghangeast@gmail.com` is actively monitored (or replace with your official `@linghangmentorship.org` support email across all 4 HTML files).
2. **Optional Mailing Address**: If Stripe requests a physical mailing address on the site matching your IRS determination letter or bank statement, add it to the `#contact` section and `<footer>` in `index.html` (and the footers of `refund.html`, `privacy.html`, `terms.html`).
3. **Stripe Dashboard Alignment**:
   - **Legal Business Name**: `Forest Program Inc` (exact match to IRS EIN letter)
   - **Employer Identification Number (EIN)**: `83-4682819`
   - **DBA / Doing Business As**: `Linghang Mentorship` or `Overture`
   - **Product Description**: Alumni community annual membership ($120.00 USD/year) and East Coast mentorship cohort fees ($300.00 USD).

## Local Preview

```sh
python3 -m http.server 8080
```

Open `http://localhost:8080/`.
