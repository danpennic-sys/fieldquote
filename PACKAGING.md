# FieldQuote Asset Packaging

## Operator tier ($349)

```
fieldquote-operator/
├── templates/
│   ├── quotes/                 # 10 JSON quote templates
│   └── invoices/               # 5 HTML invoice templates
├── data/
│   └── service_menu_example.csv
├── docs/
│   ├── service_menu_guide.md
│   ├── intake_sheet.md
│   └── job_status_board.md
├── PACKAGING.md
└── README.md
```

- Lifetime updates via versioned zip + changelog
- Support: single email, 24-hour target

---

## Command tier ($1,497)

Everything in Operator, plus:

```
fieldquote-command/
├── (all Operator files)
├── branding/
│   └── config.json             # colors, logo path, footer, license #
├── docs/
│   ├── pricing_worksheet.md
│   ├── revenue_plan_12m.md
│   ├── followup_scripts.txt
│   ├── conversion_playbook.md
│   └── call_checklists.md
└── README.md
```

- Onboarding call (60 min) + annual review checklist
- Same support channel with priority handling

---

## File inventory

### Quote templates (`templates/quotes/`)

| File | Trade |
|------|--------|
| `plumbing_fixture_install.json` | Plumbing |
| `plumbing_water_heater.json` | Plumbing |
| `plumbing_drain_clean.json` | Plumbing |
| `hvac_tuneup.json` | HVAC |
| `hvac_diagnostic.json` | HVAC |
| `electrical_panel_outlet.json` | Electrical |
| `electrical_ceiling_fan.json` | Electrical |
| `landscape_weekly.json` | Landscape |
| `handyman_halfday.json` | Handyman |
| `general_service_call.json` | General |

### Invoice templates (`templates/invoices/`)

| File | Use |
|------|-----|
| `invoice_standard.html` | Standard job invoice |
| `invoice_progress.html` | Progress / % complete |
| `invoice_service_call.html` | Flat-rate service call |
| `invoice_maintenance.html` | Recurring maintenance plan |
| `invoice_change_order.html` | Change order vs original quote |

### Docs & data

| Path | Tier |
|------|------|
| `data/service_menu_example.csv` | Operator |
| `docs/service_menu_guide.md` | Operator |
| `docs/intake_sheet.md` | Operator |
| `docs/job_status_board.md` | Operator |
| `branding/config.json` | Command |
| `docs/pricing_worksheet.md` | Command |
| `docs/revenue_plan_12m.md` | Command |
| `docs/followup_scripts.txt` | Command |
| `docs/conversion_playbook.md` | Command |
| `docs/call_checklists.md` | Command |

### Optional binaries (release assets, not in git)

- `FieldQuote_Pricing_and_Revenue_Plan.xlsx` — live formulas
- `pricing_worksheet.pdf` — printable
- `revenue_plan_12m.pdf` — printable
