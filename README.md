# Ktzefihit Smart Lead Demo

Static smart-site demo for a cafe/food-service lead-capture and owner follow-up flow.

## What This Demo Shows

- A customer-facing smart website for orders, delivery, catering trays, and questions.
- A visible inquiry form above the fold.
- A smart ordering assistant section.
- Owner-side dashboard link for lead status: who asked, what is missing, urgency, and next action.
- Local SEO and business-intent sections for Tirat Carmel food/cafe searches.

## Design Direction

The page uses a warm cafe/food-service visual direction with a conversion-focused layout:

- clear hero message
- strong primary CTA
- visible food imagery
- owner dashboard proof
- accessible contrast and large touch targets
- mobile-first stacking without horizontal overflow

## Run Locally

Open `index.html` directly in a browser, or run:

```powershell
python -m http.server 8791
```

Then open:

```text
http://127.0.0.1:8791/
```

## GitHub Pages

After pushing this repository to GitHub:

1. Open the repository on GitHub.
2. Go to `Settings`.
3. Go to `Pages`.
4. Choose `Deploy from a branch`.
5. Choose branch `main` and folder `/root`.
6. Save.

GitHub will give you a public demo link.

## Notes

This is a proof demo only. It does not send WhatsApp messages, emails, CRM updates, or real customer data.

Current production entry:

- `/` -> `index.html`
- `/smart-site.html` -> same smart site
- `/owner-dashboard.html` -> owner dashboard demo
