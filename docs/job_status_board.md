# Job-Status Board

## Columns (Kanban)

| Column     | Status value | Meaning                          |
|------------|--------------|----------------------------------|
| Draft      | draft        | Quote being built                |
| Sent       | sent         | Delivered to customer            |
| Accepted   | accepted     | Customer said yes                |
| Scheduled  | scheduled    | On the calendar                  |
| Invoiced   | invoiced     | Work done, invoice sent          |
| Paid       | paid         | Payment received                 |
| Lost       | lost         | No response / declined (7+ days) |

## Implementation notes
- Backed by `status` field on the job/quote record in SQLite.
- HTML page: simple Kanban (one column per status).
- Cards show: customer name, job type, amount, days in status.
- Drag-and-drop optional; click-to-change-status is enough for v1.

## Suggested filters
- Trade
- Date range
- Owner (if multi-user later)
