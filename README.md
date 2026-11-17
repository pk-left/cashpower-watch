# Cashpower Watch

**Live app: [setalnawec.netlify.app](https://setalnawec.netlify.app)**

A simple phone app that works out how much electricity your home uses and what it costs, for NAWEC cashpower in the Gambia.

- list your appliances (watts and hours a day) and see the kWh and cost straight away
- figures for a day, a week and a month, at D13.50 per kWh (you can change the price)
- see which appliance costs the most
- optional: read your meter to chart what you really use by day, week or month, and compare it with your list
- optional: follow the units left on your meter and what a top-up buys
- split a top-up between households that share one meter, and send a summary on WhatsApp
- live meter demo (Holal Sense): see below

## Holal Sense: live meter demo

**Try it: [setalnawec.netlify.app/sense.html](https://setalnawec.netlify.app/sense.html)**

Team Holal's entry for the GEW 2026 Green Economy Hackathon adds hardware: a small clip that sits over the cashpower meter's pulse LED and turns it into a smart meter. The demo page simulates that hardware, since there is no physical device yet.

- **The meter:** a virtual NAWEC prepaid meter whose LED blinks 1600 times per kWh, with a working keypad for tokens
- **Holal Sense:** a light sensor and ESP32 clipped over the LED count the blinks and send them to the phone over Wi-Fi or GSM. Nothing is wired into the meter
- **The home or shop:** switch appliances on and off and watch the blinks speed up
- **The phone:** live watts, units left, how long they will last, cost, a live chart, alerts for low units and big loads, and top-up from the phone
- **Pitch demo:** one button plays a one-minute story with captions: morning use, an iron alert, a low-units warning and a top-up that keeps the power on

Top-up from the phone is simulated. The real version needs a partnership with NAWEC and a mobile money provider.

## How it works

1. Add the things you plug in: lights, fans, fridge, TV, iron and so on.
2. For each one, give its watts (on the label) and how many hours a day it runs.
3. See the kWh and the cost for a day, a week and a month.
4. Optional: read your meter on the Meter tab to compare with what you really use.

It is not a NAWEC app and it cannot read your meter. Figures come from the appliances and readings you type in.

## Built with

Plain HTML, CSS and JavaScript in two files, `index.html` (the app) and `sense.html` (the live meter demo), with no frameworks. Your data is saved in your phone's browser, so nothing is sent to a server. Use **More → Backup and restore** to keep a copy.

Hosted on Netlify.

---

Made by PK
