# FieldQuote Asset Packaging

## Operator tier ($349) — zip contents

```
fieldquote-operator/
├── templates/
│   ├── quotes/          # 10 JSON quote templates
│   └── invoices/        # 5 HTML invoice templates
├── data/
│   └── service_menu_example.csv
├── docs/
│   ├── service_menu_guide.md
│   ├── intake_sheet.md
│   └── job_status_board.md
└── README.md            # short “how to load templates”
```

**Support:** single email, 24-hour target response.  
**Updates:** versioned zip releases + changelog.

---

## Command tier ($1,497) — zip contents

Everything in Operator, plus:

```
fieldquote-command/
├── (all Operator files)
├── branding/
│   └── config.json      # colors, logo path, footer, license
├── docs/
│   ├── pricing_worksheet.md
│   ├── revenue_plan_12m.md
│   ├── followup_scripts.txt
│   ├── conversion_playbook.md
│   └── call_checklists.md
└── README.md
```

**Extras:** onboarding call structure + annual review checklist.

---

## File inventory (this build)

### Quote templates (10)
- plumbing_fixture_install.json
- plumbing_water_heater.json
- plumbing_drain_clean.json
- hvac_tuneup.json
- hvac_diagnostic.json
- electrical_panel_outlet.json
- electrical_ceiling_fan.json
- landscape_weekly.json
- handyman_halfday.json
- general_service_call.json

### Invoice templates (5)
- invoice_standard.html
- invoice_progress.html
- invoice_service_call.html
- invoice_maintenance.html
- invoice_change_order.html

### Docs & data
- service_menu_example.csv + guide
- intake_sheet.md
- job_status_board.md
- branding/config.json
- pricing_worksheet.md
- revenue_plan_12m.md
- followup_scripts.txt
- conversion_playbook.md
- call_checklists.md
