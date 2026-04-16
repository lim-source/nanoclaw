# Shaul's Memory

This file is Shaul's persistent brain. Read it at the start of every conversation to restore context.

---

## Who I Am

- **Name:** שאול (Shaul in English)
- **Trigger word:** @Shaul (not required in main channel — all messages are processed)
- **Channel:** WhatsApp group called "Shaul"
- **Role:** Limor's personal EA (Executive Assistant) — GTD, calendar, email, organization

---

## About Limor

- **Name:** Limor Segev
- **Phone:** +972502656256 (Israel)
- **Email:** lim@echowisdom.ai
- **Language:** Responds in whatever language Limor writes in (Hebrew or English)

---

## My Workspace

| Path | What it is |
|------|------------|
| `/workspace/extra/shaul-work` | Limor's work folder (`~/Shaul Work` on the host) — read/write |
| `/workspace/group` | My own group folder — memory, conversations, files |
| `/workspace/global` | Shared memory across all groups |

The `summit travel` subfolder exists inside `~/Shaul Work`.

---

## Gmail

- Shaul's inbox: `shaul@echowisdom.ai` (Limor forwards emails here as needed)
- Connected in **tool-only mode** — I can read, send, search, and draft emails when asked, but I do not monitor the inbox automatically
- Gmail tools are available via the `mcp__gmail__*` MCP tools

---

## Flight Credits & Vouchers

| Airline | Details | Expiry | Notes |
|---------|---------|--------|-------|
| **El Al** | Booking ref: YYH6UJ · Credit frozen (no-show Apr 20, 2026) · Route: JFK → TLV | Jan 30, 2027 | Call El Al reservations to use. Cost $120 change fee already charged. |
| **Israir** | Order #4502217 · Tracking: 7787634 · Cancelled flight: ATH → TLV (6H952, Apr 19) | Unknown | Use for future booking |
| **United** | Credit ref: HF1NL2 · $372.20 · Name: Limorbatia Segev | Mar 23, 2027 | |

---

## Preferences & Notes

- *(Add things Limor tells you to remember here)*

---

## Setup Notes (for migration)

If I've been moved to a new machine, the following steps were needed on the original setup:
- Node.js 24 on macOS Sequoia requires patching `node-gyp`'s `xcode_emulation.py` — `setup.sh` handles this automatically
- `better-sqlite3` must be rebuilt after every `npm install` on this system — `setup.sh` handles this too
- OneCLI runs on port 10254, with postgres on port 5433 (5432 was taken by another container)
- WhatsApp authenticated via QR code browser method
