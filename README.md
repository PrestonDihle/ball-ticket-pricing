# Ball Ticket Pricing

A single-page dashboard for working out ball ticket prices. Change costs, attendance and funding to see the break-even price and the surplus or shortfall at any ticket price.

Open `index.html` in a browser. There is nothing to build or install. The page loads its fonts from Google Fonts and falls back to system fonts when offline.

## Baseline

The starting figures come from the ball funding and cost worksheet: €66,583.67 in costs, €52,583.67 net of offsets, and €87.64 per ticket at 600 tickets.

- Venue cost is fixed at €11,808.67.
- Ticket sales are capped at 624, with a jump point at 480 for the alternate seating arrangement.

## How the worksheet was read

The sheet gives totals and a few notes. These rates were worked out from it so that each figure can move. Check them against what you know.

- **Meal, €45 per guest:** €27,000 ÷ 600 tickets.
- **Wine, €4 per guest:** stated in the sheet.
- **Table gifts, €4 per guest:** €2,400 ÷ 600. If gifts are bought per table, this cost will not track tickets this closely.
- **Beer, €150 per keg:** €600 ÷ 4 kegs.
- **VIP, 50 guests:** €5,000 ÷ the €100 upgrade. VIPs are counted within tickets sold.
- **Childcare, 200 children at €30 each:** €4,000 ÷ the €20 parent fee, then €6,000 ÷ 200. The sheet's childcare row also says "50xpassengers", which doesn't fit 200 children, so confirm this headcount.
- **Bus riders, 50 / 20 / 50:** from the notes beside each bus, read as riders per bus. Bus costs stay flat when riders change. The fare starts at €0 because the sheet shows no bus fare.
- **Checkpoint at 480, ceiling at 624:** ticket sales can't go above 624. The checkpoint is a jump point for the 480 seating arrangement, and it changes only the ticket count.
- **Stays flat as tickets change:** venue, buses, childcare, beer, entertainment, keg mallets, raffle gifts and unplanned expenses.
