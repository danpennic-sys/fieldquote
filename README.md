# FieldQuote — Operator & Command Asset Pack

Concrete templates and docs for the FieldQuote quoting app.

## Quick start

1. **Quote templates** — load any JSON from `templates/quotes/` into the app.
2. **Invoice templates** — HTML files in `templates/invoices/` (Handlebars-style placeholders).
3. **Branding** — edit `branding/config.json` (Command tier).
4. **Service menu** — edit `data/service_menu_example.csv`, then hit `/service-menu`.

## Operator vs Command

| Asset | Operator ($349) | Command ($1,497) |
|-------|-----------------|------------------|
| 10 quote templates | ✓ | ✓ |
| 5 invoice templates | ✓ | ✓ |
| Service menu CSV + guide | ✓ | ✓ |
| Intake sheet | ✓ | ✓ |
| Job-status board notes | ✓ | ✓ |
| Branding config | — | ✓ |
| Pricing worksheet | — | ✓ |
| 12-month revenue plan | — | ✓ |
| Follow-up scripts | — | ✓ |
| Conversion playbook | — | ✓ |
| Call checklists | — | ✓ |

See `PACKAGING.md` for zip layout and support notes.

## Binary assets (local)

Excel + PDF versions of the pricing worksheet and revenue plan are in the local `fieldquote-assets.zip` release:
- `docs/FieldQuote_Pricing_and_Revenue_Plan.xlsx`
- `docs/pricing_worksheet.pdf`
- `docs/revenue_plan_12m.pdf`
