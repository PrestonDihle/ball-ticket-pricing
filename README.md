# Ball Ticket Pricing

A single-page dashboard for working out ball ticket prices. Change costs, attendance and funding to see the break-even price and the surplus or shortfall at any ticket price.

Open `index.html` in a browser. There is nothing to build or install. The page loads its fonts from Google Fonts and falls back to system fonts when offline.

## Baseline

The starting figures come from the ball funding and cost worksheet, with these changes: 50 children at €80 each with a €20 parent fee, a €20 bus fare, wine at €2 per guest and a €85 ticket price. That gives €63,383.67 in costs, €49,983.67 net of offsets, and €83.31 per ticket at 600 tickets, for a €1,016.33 surplus at €85.

- Venue cost is fixed at €11,808.67.
- Ticket sales are capped at 624, with a jump point at 480 for the alternate seating arrangement.

## Dollar conversion

The ticket price in the top band also shows in US dollars. The rate starts at $1.1179 per euro, the European Central Bank rate for 3 November 2026, and doesn't update by itself. Edit it in the band when you need a newer rate. All other amounts stay in euros.

## Pricing by rank

Switch the Pricing model card to **By rank** to estimate attendance and set a separate price for each rank group and for civilians. Added groups and Civilians can be removed. The brigade's rank groups stay.

- **Brigade totals:** the 1,205 people across seven groups are fixed: E1-E4 480 (40%), E5-E6 375 (31%), E7-E9 65 (5%), W1-W2 140 (12%), W3-W5 45 (4%), O1-O3 85 (7%) and O4-O6 15 (1%). The % of population column can't be edited.
- **Attendees:** total in category × likely participation × (1 + % who bring a date), rounded to a whole number. Dates pay their group's price.
- **Tickets sold:** follows the attendee total once a participation rate is entered. A total over the 624 ceiling is scaled down to fit. Moving tickets sold or jumping to 480 scales each group the same way, and a button returns to the forecast.
- **Estimates to enter:** participation and date rates start blank. Until a participation rate is entered, tickets sold are split by % of population. A blank date rate counts as 0%.
- **Civilians:** they aren't in the brigade totals, so they take a typed attendee count, starting at 0. Added groups work the same way.
- **VIP extra charge:** this still applies on top of rank prices, so set VIP guests to 0 if a rank price already includes it.

## How the worksheet was read

The sheet gives totals and a few notes. These rates were worked out from it so that each figure can move. Check them against what you know. The baseline has since replaced the sheet's wine, childcare and bus fare figures, and its €90 ticket price.

- **Meal, €45 per guest:** €27,000 ÷ 600 tickets.
- **Wine, €4 per guest in the sheet:** the baseline now uses €2.
- **Table gifts, €4 per guest:** €2,400 ÷ 600. If gifts are bought per table, this cost will not track tickets this closely.
- **Beer, €150 per keg:** €600 ÷ 4 kegs.
- **VIP, 50 guests:** €5,000 ÷ the €100 upgrade. VIPs are counted within tickets sold.
- **Childcare, 200 children at €30 each in the sheet:** €4,000 ÷ the €20 parent fee, then €6,000 ÷ 200. The baseline now uses 50 children at €80 each with the same €20 fee.
- **Bus riders, 50 / 20 / 50:** from the notes beside each bus, read as riders per bus. Bus costs stay flat when riders change. The sheet shows no bus fare, and the baseline now uses €20 per rider.
- **Checkpoint at 480, ceiling at 624:** ticket sales can't go above 624. The checkpoint is a jump point for the 480 seating arrangement, and it changes only the ticket count.
- **Stays flat as tickets change:** venue, buses, childcare, beer, entertainment, keg mallets, raffle gifts and unplanned expenses.
