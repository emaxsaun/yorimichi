# ヨリミチ — Yorimichi

**A quiet Japanese convenience-store visit you can take any time you miss it.**

🔗 **Play it:** https://emaxsaun.github.io/yorimichi/  
🎮 **Walkable RPG version:** https://emaxsaun.github.io/yorimichi/rpg/

## Features

- 🍙 Authentic konbini shopping experience
- 🚃 Walk or ride the train
- 🌸 Four seasons and four times of day
- 🧾 Thermal receipts
- 💳 IC card, cash, QR code, or credit payment
- 📖 Persistent Konbini Passport shared between both versions
- 🎵 Browser-synthesized audio
- 🕹️ Two complete ways to play

Yorimichi (寄り道 — "a little detour on the way home") is a tiny, cozy Japanese convenience-store simulator. You're not running the store—you're simply stopping by. Pick a time of day and a season, walk or take the train over, wander the shelves, tap your card, and eat something good somewhere quiet. It's a small cure for the ache you feel after a trip to Japan ends.

No goals, no timers, no pressure.
Just the calm of a 24-hour convenience store at whatever hour you need it.

---

## Two ways to visit

- **Classic** — a soft, card-based visit. Browse the aisles like a menu, tap what you want, check out. Calm and quick.
- **Walkable RPG** — the same store rebuilt as a retro pixel-art world. Actually *walk* the street, ride a little pixel train, wander the aisles tile by tile, and talk to the clerk face to face. Everything—the UI, the products, the receipt stamp, the riverside where you eat—is hand-drawn in 16×16 pixel art.

Each version links to the other from its title screen, and your Konbini Passport carries across both.

---

## What you can do

- **Set the scene** — choose morning, daytime, evening, or late night, and spring, summer, autumn, or winter. The light, the stock, and the music all change with it.
- **Get there** — stroll past a glowing vending machine, or catch the train to ヨリミチ前駅. (In the RPG version, you really walk it—and the vending machine really sells.)
- **Browse the aisles** — onigiri, sandwiches, hot foods, drinks, snacks & sweets, ice cream, rotating seasonal specials, and limited-time items. Take the clerk's recommendation if you like.
- **Check out for real** — "Would you like it warmed up?", a ¥3 bag or your own, the point card... then pay by IC card, cash, QR, or credit, all using a shared rechargeable balance.
- **Keep the receipt** — a little thermal receipt prints out.
- **Eat somewhere quiet** — sit with what you bought.
- **Fill your Konbini Passport** — every item you've ever tried, your visit stats, points, and a shelf of achievement stamps, saved between visits.

---

## Controls (RPG version)

**On a phone** — drag the joystick to walk, or just tap where you want to go and you'll walk there. Tap Ⓐ (or the thing itself) to interact.

**On a keyboard:**

| Keys | Action |
| --- | --- |
| `W A S D` / `↑ ↓ ← →` | Move |
| `E` `B` `Space` `Enter` | Interact with what you're facing |
| `Esc` (or `X`) | Close a panel / step back |
| `1`–`9` | Add items while browsing a shelf |
| `I` | Basket |
| `P` | Passport |
| `M` | Sound on/off |

Desktop supports the virtual joystick too—you can drag to walk or simply click/tap where you'd like to go.

---

## Get the full-screen experience (iOS)

In Safari, tap the **Share** button → **Add to Home Screen**. Launched from the home screen it runs full-screen with no browser chrome—the closest thing to a real little app.

---

## Built with

- **Two single, self-contained HTML files** (one per version)—no build step, no frameworks, no external asset files.
- **Vanilla JavaScript** for everything.
- **Inline SVG** for all the art in the classic version.
- A **canvas tile engine** for the RPG version with hand-drawn 16×16 pixel tiles and sprites, time-of-day tinting, virtual joystick, tap-to-walk pathfinding, and full keyboard support.
- **Web Audio API** for all the sound—everything is synthesized in the browser, with no audio files loaded.
- **localStorage** for your passport and balance (shared between both versions).
- The only external dependency is Google Fonts (including Press Start 2P and DotGothic16 for the RPG).

It's deliberately portrait-first and zoom-locked on phones for a stable, app-like feel; on desktop the RPG letterboxes to keep the whole scene in view.

---

## Running it yourself

The project is intentionally simple: two standalone HTML files.

Open `index.html` in any modern browser (the RPG lives at `rpg/index.html`), or serve the folder with anything (for example, `python3 -m http.server`). To host your own copy, simply place the folder at the root of a GitHub Pages repository.

---

## A note

This is a personal project—made solo, with AI as an occasional pair programmer, for the love of konbini and the quiet corners of Japan.

Take your time.
いってらっしゃい.
