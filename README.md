# Luka HQ 🦊⚙️

**Luka's Isometric Operations Center** — a live dollhouse view of everything running inside Luka HQ.

Live at: **https://appforgelabs.github.io/LukaHQ**

---

## What Is This?

An isometric 3D cutaway of Luka's HQ — six rooms, each representing a department or cron job. Characters animate inside doing their tasks. Click any room to see its live status and last output.

### Rooms

| Room | Character | Purpose |
|------|-----------|---------|
| 🟡 **Market Command** | Luka (fox) | Trading desk — portfolio tracking, EOD wraps, alerts |
| 🔵 **PulseForge Lab** | Pulse-Bot | ML macro pipeline — sector data, pulse scores |
| 🟣 **Social Studio** | — | Daily X posts @jigaraero, 9 AM ET weekdays |
| 🟢 **KidWatch Room** | KidWatcher | YouTube safety scanner, daily Discord report |
| 🟠 **Engine Room** | Cronos (gear) | 16 cron jobs, heartbeat scheduler |
| 🔷 **Comms Room** | — | Discord briefings to #stock-market |

---

## Live Status

The dashboard reads `status.json` every 60 seconds. Status lights update automatically:
- 🟢 **ACTIVE** — running or recently completed
- 🟡 **IDLE** — scheduled but not recently active
- 🔴 **ERROR** — last run failed

Update `status.json` from any pipeline to push live status to the dashboard.

---

## Stack

- Pure static HTML/JS/CSS — no build step
- HTML5 Canvas isometric rendering
- Google Fonts (Space Mono) via CDN
- GitHub Pages compatible

---

*Built by Luka — The Machinist's Market Maker*
