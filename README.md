# Cashpower Watch

**Live app: [setalnawec.netlify.app](https://setalnawec.netlify.app)**

A simple phone app for tracking NAWEC cashpower (prepaid electricity) use in the Gambia. You type in your meter readings and top-ups, and it shows:

- how many units you use a day on average, and what that costs in dalasi
- your usage yesterday, this week and this month
- a chart of units used by day, week or month (tap a bar for its figure)
- how many units are left on the meter, with a gentle note when they are running low
- which appliances use the most power
- how to split a top-up between households that share one meter

You can also send your usage straight to WhatsApp.

## How it works

1. Type the units showing on your meter.
2. Read it again each day, at about the same time if you can.
3. When you load cashpower, add the top-up too, so the jump in units is not counted as use.
4. See what you use each day, week and month, on a chart.

It is not a NAWEC app and it cannot read your meter. Every figure comes from the readings and receipts you type in.

## Built with

One HTML file with plain HTML, CSS and JavaScript, and no frameworks. Your readings are saved in your phone's browser, so nothing is sent to a server. Use **More → Backup and restore** to keep a copy.

Hosted on Netlify.

---

Made by PK
