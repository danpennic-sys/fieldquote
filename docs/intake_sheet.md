# Customer Intake Sheet

## Fields (map to customer / job table)

| Field              | Type     | Required | Notes                          |
|--------------------|----------|----------|--------------------------------|
| name               | text     | yes      | Full name                      |
| address            | text     | yes      | Service address                |
| phone              | text     | yes      | Primary contact                |
| email              | text     | no       | For quote delivery             |
| preferred_contact  | enum     | no       | phone / text / email           |
| job_type           | text     | yes      | e.g. Plumbing, HVAC            |
| urgency            | enum     | no       | same-day / this-week / flexible|
| notes              | textarea | no       | Free-form details              |
| source             | text     | no       | How they found you             |

## Formats
1. **In-app form** — writes directly to SQLite customer + job tables.
2. **Printable PDF** — blank form for truck use; photo or re-enter later.

## Suggested status on create
New intake → job status = `Draft`
