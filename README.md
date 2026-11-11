# Cashpower Watch

**Live app: [setalnawec.netlify.app](https://setalnawec.netlify.app)**

A simple phone app for NAWEC cashpower (prepaid electricity) in the Gambia. You type in your meter readings and top-up receipts, and it tells you:

- how many units you have left right now, and how many days they will last
- the day to buy by, before the units run out
- how many units you use in a day and what that costs you in dalasi
- how long a top-up of any amount will last
- which appliances use the most power
- how to split a top-up between households that share one meter

You can also send the status straight to WhatsApp.

## How it works

1. Type the units showing on your meter.
2. Do it again the next day. The app now knows how many units you use in a day.
3. Add each top-up: what you paid and the units on the receipt.
4. See how many days are left, the day to buy by, and the cost per day.

It is not a NAWEC app and it cannot read your meter. Every figure comes from the readings and receipts you type in.

## Built with

One HTML file with plain HTML, CSS and JavaScript, and no frameworks. Your readings are saved in your phone's browser, so nothing is sent to a server. Use **More → Backup and restore** to keep a copy.

Hosted on Netlify.

---

Made by PK
