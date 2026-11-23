# talentpay

Landing page for **talentpay** — a contractor of record for small and mid-size teams in the EU and US. Pay anyone, anywhere. Calmly. $39 per payment.

## Structure

- `index.html` — the landing page (static, no build step)
- `styles.css` — styles; color and type tokens follow `BRAND.md`
- `assets/img/` — mascot Pifi (SVG), illustrations, contractor portraits
- `assets/flags/` — round country flags from [flag-icons](https://github.com/lipis/flag-icons) (MIT)
- `BRAND.md` — brand identity: positioning, voice, colors, type, illustration rules

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Hosting

Served by GitHub Pages from the `main` branch root.

## Before launch

- Replace the placeholder testimonial with a real customer quote.
- Keep only the payment rails your payment partner actually supports.
- Contractor portraits and illustrations are AI-generated, not real people.
