# New London Trades Businesses Daily — Landing Page

Static marketing site for the London Trades Daily feed, a daily digest of newly incorporated London construction and trades businesses sourced from Companies House. Built for accountants, bookkeepers, and professional service firms who want to reach new businesses early.

## Live site

https://brahma272462.github.io/london-trades-daily-site/

## Deploy via GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select **Deploy from a branch**.
4. Set branch to `main`, folder to `/ (root)`.
5. Save. The site will be live within a minute or two.

No build step required — GitHub Pages serves the files directly.

## How to update the sample companies

Open `index.html` and find the `<tbody>` inside the **"Real companies from a recent daily feed"** section. Edit or replace the `<tr>` rows. Each row has three cells: **Company**, **Trade**, **Postcode** — there is no date column.

## How to update the payment link

Search `index.html` for `londontradesdaily.lemonsqueezy.com` and replace the full URL with the new Lemon Squeezy checkout link.

## How to update the Google Form link

Search `index.html` for `forms.gle` and replace the URL with the new form link. It appears on the **Request a free sample** button.

## How to change the price

Search `index.html` for `£49`. It appears in two places:

1. The visible price display inside `.pricing-card`.
2. The primary CTA button — `Subscribe — £49/month`.

## How to update the pricing card supporting lines

The two small lines below the price ("Around 30p per new business lead..." and "Full refund within 14 days...") are `.price-value-line` and `.price-refund-line` inside `.pricing-card` in `index.html`.
