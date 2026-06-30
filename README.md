# ヨリミチ — Yorimichi

**A quiet Japanese convenience-store visit you can take any time you miss it.**

🔗 **Play it:** https://emaxsaun.github.io/yorimichi/

Yorimichi (寄り道 — "a little detour on the way home") is a tiny, cozy *konbini* simulator. You're not running the store — you're just **visiting**. Pick a time of day and a season, walk or take the train over, wander the shelves, tap your card, and eat something good somewhere quiet. It's a small cure for the ache you feel after a trip to Japan ends.

No goals, no timers, no pressure. Just the calm of a 24-hour convenience store at whatever hour you need it.

---

## What you can do

- **Set the scene** — choose morning, daytime, evening, or late night, and spring, summer, autumn, or winter. The light, the stock, and the music all change with it.
- **Get there** — stroll past a glowing vending machine, or catch the train to ヨリミチ前駅.
- **Browse the aisles** — onigiri, sandwiches, hot foods, drinks, snacks & sweets, ice cream, and rotating seasonal & limited picks. Take the clerk's recommendation if you like.
- **Check out for real** — "Would you like it warmed up?", a ¥3 bag or your own, the point card... then pay by IC card, cash, QR, or credit, all drawn from one balance you can recharge.
- **Keep the receipt** — a little thermal receipt prints out.
- **Eat somewhere quiet** — sit with what you bought.
- **Fill your Konbini Passport** — every item you've ever tried, your visit stats, points, and a shelf of achievement stamps, saved between visits.

---

## Get the full-screen experience (iOS)

In Safari, tap the **Share** button → **Add to Home Screen**. Launched from the home screen it runs full-screen with no browser chrome — the closest thing to a real little app. (The site nudges you toward this the first time, too.)

---

## Built with

- A **single, self-contained `index.html`** — no build step, no frameworks, no external asset files.
- **Vanilla JavaScript** for everything.
- **Inline SVG** for all the art (every product, the storefront, the train, the receipt).
- **Web Audio API** for all the sound — the door chime, the register beep, the IC-card *pi!*, the ambient hum and music are all synthesized in the browser, nothing is loaded.
- **localStorage** for your passport and balance.
- The only external dependency is Google Fonts.

It's deliberately portrait-only and zoom-locked for a stable, app-like feel.

---

## Running it yourself

It's one file. Open `index.html` in any modern browser, or serve the folder with anything (e.g. `python3 -m http.server`). To host your own copy, drop `index.html` at the root of a GitHub Pages repo and you're done.

---

## A note

This is a personal project — made solo (with a little AI pair-programming) for the love of konbini and the quiet corners of Japan. Take your time. いってらっしゃい.
