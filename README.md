# POWER — The Board Game (1981)

A faithful digital recreation of **Power** by Monte B. Young (Power Games International / Spear's Games, 1981 — later "Power: The Game", 1995 edition). Local hotseat play for 2–4 players, no install, no internet.

## How to play

**Play online:** https://pejavrajich8.github.io/power-the-game/ — or just open `index.html` in any browser. Everything is in that one file.

Two ways to play:

- **🛋 Hotseat** — everyone shares one device, passing it around to write secret orders.
- **🌐 Online multiplayer** — one player hosts and gets a 4-letter room code; friends pick "Join online game" and enter the code. Everyone plans their secret orders **simultaneously on their own device** (free peer-to-peer WebRTC — no accounts, no server). If someone drops, they can rejoin with the same name and room code.

Player counts:

- **2 players** — each commands two adjacent countries (official 2-player rules: 10 commands, separate reserves, combined combat strength).
- **3 players** — the fourth country fights as **mercenaries**; anyone may spend commands on them, and clashing mercenary orders cancel out (official rule).
- **4 players** — the classic free-for-all.

Each round every player secretly writes up to **5 commands** (optional authentic 3-minute timer), then all orders execute **simultaneously** — Diplomacy style.

## The rules in 60 seconds

| Piece | Moves | Power | | Piece | Moves | Power |
|---|---|---|---|---|---|---|
| Infantry | 2 | 2 | 3 ⇒ | Regiment | 2 | 20 |
| Tank | 3 | 3 | 3 ⇒ | Heavy Tank | 3 | 30 |
| Fighter | 5 | 5 | 3 ⇒ | Bomber | 5 | 25 |
| Destroyer | 1 | 10 | 3 ⇒ | Cruiser | 1 | 50 |
| Megamissile | any | 0 (defence) | | 100+ power to build, one shot | | |

- Ground units stop on islands and HQs; they cross between countries via the islands.
- Planes may overfly islands but **never sea lanes**.
- Ships move one water area per round and can never reach a country's center sector.
- Combat: highest total power in a sector **captures** every weaker force there (captured pieces convert to your colour — limited by your spare pieces). Ties bounce the movers back.
- Occupy enemy countries to earn **Power Units** (1 per country per round, max 3, hold max 10) and buy reinforcements in your reserve.
- Capture enemy flags **with Infantry or a Regiment in the HQ**. Last flag standing wins.

## Sources

Rules were reconstructed from the original publisher's rulebook and period sources:

- Official PGI rulebook (English/Danish/German), archived from powergames.com — saved here as `original-rules.txt`
- [BoardGameGeek — Power (1981)](https://boardgamegeek.com/boardgame/487/power) (game data, board photos, rules forum threads)
- [Wayback Machine — powergames.com](https://web.archive.org/web/2003/http://powergames.com/) (board art, piece imagery)

Built with Claude Code as a fan recreation for personal/educational use.
