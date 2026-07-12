# 🔥 Churrasco Meat Price Tracker — Ottawa

An interactive, single-file web app for comparing meat prices across Ottawa shops for a
Brazilian barbecue (churrasco). Enter a price, weight, and unit (kg / lb / oz) and it
normalizes everything to **$/kg** and **$/lb** so you can compare fairly, and highlights the
cheapest option for each cut.

## Features

- **Automatic unit conversion** — mix kg, lb, and oz; comparison is always apples-to-apples.
- **Cheapest-per-cut highlighting** — the best-value row for each cut turns green.
- **Category filter** — toggle between 🇧🇷 Brazilian churrasco cuts and other cuts, with a flag on each group.
- **Grade column** — regulated Canada grades (AAA / AA / A / Prime) vs "Angus" breed marketing vs "n/s" (not stated).
- **Grill rating** — a strict 0–5 star score for how good each cut is for the barbecue; click to edit.
- **Offer links** — each row links to the product page; links that only reach a store/search/category
  page are flagged with an orange "browse ⚠" so you know to verify the item.
- **Editable inline** — change price, weight, unit, grade, rating, notes, and links right in the table.
- **Add your own items** — including a link.
- **Saves automatically** — all your edits persist in your browser (localStorage).

## Pre-loaded shops

Costco, Real Canadian Superstore, Wiser Meats, Ottawa Valley Meats, Farm 2 Fork,
Slipacoff's Premium Meats, The Piggy Market, and Nosso Talho (flagged — Toronto delivery only).
Live prices were fetched in July 2026 and are a snapshot — verify before buying.

## Usage

Just open `index.html` in any browser. No build step, no dependencies, no server required —
everything (HTML, CSS, JavaScript, and seed data) is in the one file.

## Notes

- Prices change; treat the pre-loaded numbers as a starting point.
- Data is stored per-browser in localStorage, so it is not shared between visitors — each person
  starts from the seed data and their own edits stay on their device.
- Grades are as stated on each shop's listing; "n/s" means the listing didn't state a grade.

## License

Personal project — use freely.
