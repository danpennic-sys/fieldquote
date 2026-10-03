# FieldQuote — Operator & Command Asset Pack

Templates and docs for FieldQuote, the local-first quoting app for trades.

**Owner:** Operator Pages · `danpennic-sys`

---

## Quick start

1. Load any JSON from `templates/quotes/` as a quote template.
2. Render invoices from `templates/invoices/` (Handlebars-style placeholders).
3. (Command) Edit `branding/config.json` for logo, colors, and footer.
4. Edit `data/service_menu_example.csv` for the printable service menu.

---

## What's included

| Asset | Operator ($349) | Command ($1,497) |
|-------|:---------------:|:----------------:|
| 10 quote templates (JSON) | Yes | Yes |
| 5 invoice templates (HTML) | Yes | Yes |
| Service menu CSV + guide | Yes | Yes |
| Customer intake sheet | Yes | Yes |
| Job-status board notes | Yes | Yes |
| Branding config | | Yes |
| Pricing worksheet | | Yes |
| 12-month revenue plan | | Yes |
| Follow-up scripts | | Yes |
| Conversion playbook | | Yes |
| Onboarding + annual review checklists | | Yes |

---

## Layout

```
fieldquote/
├── branding/
│   └── config.json
├── data/
│   └── service_menu_example.csv
├── docs/
│   ├── call_checklists.md
│   ├── conversion_playbook.md
│   ├── followup_scripts.txt
│   ├── intake_sheet.md
│   ├── job_status_board.md
│   ├── pricing_worksheet.md
│   ├── revenue_plan_12m.md
│   └── service_menu_guide.md
├── templates/
│   ├── invoices/          # 5 HTML templates
│   └── quotes/            # 10 JSON templates
├── CHANGELOG.md
├── LICENSE
├── PACKAGING.md
└── README.md
```

---

## Quote template schema

```json
{
  "name": "Template display name",
  "trade": "Plumbing | HVAC | Electrical | Landscape | Handyman | General",
  "default_tax_pct": 8.5,
  "default_deposit_pct": 30,
  "items": [
    { "description": "Line item", "qty": 1, "unit_price": 95 }
  ]
}
```

## Invoice placeholders

Common tags: `{{business_name}}`, `{{customer_name}}`, `{{invoice_number}}`, `{{items}}`, `{{subtotal}}`, `{{tax_amount}}`, `{{balance_due}}`, `{{primary_color}}`, `{{footer_text}}`.

See each HTML file for template-specific fields (progress %, change-order delta, plan name, etc.).

---

## Support

- **Operator:** email support, 24-hour target response
- **Command:** includes onboarding call + annual review structure (see `docs/call_checklists.md`)

Updates ship as versioned releases. See `PACKAGING.md` for zip layouts.

---

## License

Proprietary — Operator Pages. Distributed only to licensed Operator / Command customers.
