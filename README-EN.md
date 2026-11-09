# 📡 Morse Practice RU (Offline Fork)

> **Free • Open Source • Browser-Based Morse Code Training Platform**  
> Russian-alphabet support + fully offline (no external servers). PWA-installable.

🇷🇺 [Русский (по умолчанию)](README.md) · 🇪🇸 [Español](README-ES.md)

## 🚀 [TRY IT NOW](https://agenticaijs.github.io/morse-practice-ru/)

> No installation · No registration · 100% free · **Works fully offline** after the first load.
> Can be installed as a PWA on the home screen and opened without internet.

This is a fork of [**ZP5DXS/morse-practice**](https://github.com/ZP5DXS/morse-practice) by Mathias Maidana (ZP5DXS).  
Original UI: English + Spanish. This fork adds Russian interface and Russian Morse alphabet support.  
Original project remains under MIT license (see [LICENSE](LICENSE)).

### Changes in this offline build

- **Removed / disabled** all features that require third-party servers:
  - Global visitor / country / practice-hour counters
  - “73” likes and appreciation counter
  - Weekly leaderboards and per-game rankings
  - ON AIR shared channel (MQTT)
  - Multiplayer DUEL matchmaking
  - IP geolocation and remote stats API
- **Kept** everything that runs locally in the browser: CW oscillator, decoder, straight key & paddles, Koch course, Listen, Racer, single-player games, local QSO simulator, custom lessons, local progress (localStorage), themes.
- Added **RU** language button, **A–Z ⇄ А–Я** script toggle, Morse correspondence table, and dual-alphabet decoder.

### How to use Russian mode

1. Open the [trainer](https://agenticaijs.github.io/morse-practice-ru/) — the default UI language is Russian.
2. Switch language with the **RU / EN / ES** buttons in the header.
3. Selecting Russian automatically switches the alphabet to **А–Я** (use the **A–Z ⇄ А–Я** toggle to switch back to Latin).
4. Use the **📋** button for the Latin ↔ Russian Morse table.

### What still works offline

- CW sidetone, WPM, Farnsworth, band noise
- Straight key & paddles (mouse, touch, USB HID)
- Koch course, challenges, adaptive practice, custom lessons
- Listen / head-copy
- Racer, Invaders, Battleship, Timing, Flappy (single-player)
- Local QSO bot simulator
- Local error statistics and progress
- Themes and most unlockable rewards that do not require network

### What is disabled

- Global stats and counters  
- “Send 73” button  
- Leaderboards / rankings  
- ON AIR and network DUEL  
- Any calls to `practice-api.zp5dxs.org` or public MQTT brokers  

`server-vps.js` has been removed from the repo — the static frontend needs no server.

---

## Credits & License

MIT. Original work © Mathias Maidana (ZP5DXS) — [ZP5DXS/morse-practice](https://github.com/ZP5DXS/morse-practice).  
Fork: [agenticaijs/morse-practice-ru](https://github.com/agenticaijs/morse-practice-ru).

73 and thanks to the original author.
