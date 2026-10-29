# The Plant Shack Stickers

A web page staff use to print "PLANT $" price stickers on the Zebra GK420t (40 × 28 mm labels).

- Open the site in Chrome on a shop computer and bookmark it.
- Zebra Browser Print must be installed and running on that computer.
- Choose the sticker printer once in the Printer box. Each computer remembers its own choice.

Prices come from the Stock Manager export: only items named exactly `PLANT $<price>` in the Plants department (Plants tab) and `POT $<price>` in any department (Pots tab). To update them, export from Stock Manager and click **Load a newer stock export** on the page (that computer only), or replace the price list in `index.html` so every computer gets it.

`plant-prices.csv` is the cleaned price list the page was built from.
