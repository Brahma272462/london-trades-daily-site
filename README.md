# New London Trades Businesses Daily — Landing Page

Static marketing site for the London Trades Daily feed, a daily digest of newly incorporated London construction and trades businesses sourced from Companies House. Built for professional service firms who want to reach new businesses early.

## Live site

https://Brahma272462.github.io/london-trades-daily-site

## Deploy via GitHub Pages

1. Push this repo to GitHub (already done).
2. Go to **Settings → Pages**.
3. Under **Source**, select **Deploy from a branch**.
4. Set branch to `main`, folder to `/ (root)`.
5. Save. The site will be live within a minute or two.

No build step required — GitHub Pages serves the files directly.

## How to update the sample companies

Open `index.html` and find the `<tbody>` inside the **"Real companies from a recent daily feed"** section. Edit or replace the `<tr>` rows with new data. Each row has four cells: Company, Trade, Postcode, Incorporated.

## How to update the Stripe link

Search `index.html` for `https://example.com/stripe` and replace it with your real Stripe payment link.

## How to update the Google Form link

Search `index.html` for `https://example.com/form` and replace it with your real Google Form or Typeform link.

## How to change the price

The price appears in two places in `index.html`:

1. Inside the `.pricing-box` — the visible `£49` figure.
2. On the primary CTA button — `Subscribe — £49/month`.

Search for `£49` to find both.
