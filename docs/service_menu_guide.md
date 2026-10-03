# Service Menu Generator

## Purpose
Produce a clean one-page “Services & Starting Prices” sheet customers can keep.

## Input
CSV file with columns:
- `service` — name of the job
- `starting_price` — number (no $ sign)
- `notes` — short description / inclusions

Example: `data/service_menu_example.csv`

## App endpoint
`GET /service-menu?source=path/to/file.csv`

Renders a printable HTML page with:
- Business header (from branding config)
- Table of services + starting prices + notes
- Footer with “Prices are starting estimates; final quote after site visit”

## Usage tips
- Keep the list to 8–15 items so it fits one page.
- Use “starting at” language so customers expect a real quote.
- Update prices quarterly; regenerate the PDF and leave copies in the truck.
