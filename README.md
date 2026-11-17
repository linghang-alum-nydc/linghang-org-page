# Forest Program Inc — Public Organization Page

Static, public-facing website (no login wall) for **Forest Program Inc** (U.S. 501(c)(3) nonprofit organization, EIN `83-4682819`), fulfilling Stripe account activation and website verification requirements.

## Structure

- `index.html` — Organization overview, Alumni Association Annual Membership ($120.00 USD/year), legal entity details, and customer support contact information.
- `refund.html` — Standalone Refund & Cancellation Policy (linked in footer).
- `privacy.html` — Standalone Privacy Policy (linked in footer).
- `terms.html` — Standalone Terms of Service (linked in footer).
- `styles.css` — Responsive stylesheet matching the Overture visual design tokens.
- `assets/lh-web-logo.png` — Organization emblem.
- `vercel.json` — Clean URL routing for static hosting on Vercel.

## Stripe Dashboard Alignment

- **Legal Business Name**: `Forest Program Inc`
- **Employer Identification Number (EIN)**: `83-4682819`
- **Support Email**: `alumni@nydc.linghangmentorship.org`
- **Product Description**: Alumni Association Annual Membership ($120.00 USD / year)

## Local Preview

```sh
python3 -m http.server 8080
```

Open `http://localhost:8080/`.
