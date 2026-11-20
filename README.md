# GIKI-TransitPulse

A fast, closed-access Windows terminal shell for **GIKI Transport** (`giktransport.giki.edu.pk`) — featuring automated opening-time booking, MWALLET recharge, persistent local sessions, and built-in GitHub auto-updates.

> **Private Release Distribution**: This repository hosts compiled `.exe` releases only. Source code is not published here.

---

## Key Features

- **Auto-Fire Ticket Sniper**: Lock your preferred **City**, **Direction** (`Inbound` / `Outbound` / `Both`), **Stops**, and **Departure Times** in advance. When the booking window opens, `GIKI-TransitPulse` pre-warms your session, burst-polls for availability, and fires parallel holds + confirmation automatically.
- **Zero-Flicker Interactive Terminal UI**: Double-buffered ANSI interface with arrow-key navigation, live 1-second PKT countdowns, and bordered ticket cards.
- **Booked Tickets & Boarding Pass**: View all booked student tickets (`[T]`) with `#ticket_code`, stops, PKT departure time, and full-screen pass details.
- **MWALLET Wallet Recharge**: Top up G-Bux directly from the shell (`[W]`) with live limit checking and JazzCash confirmation support.
- **Fast Session Persistence & Auto-Relogin**: Saves session tokens, cookies, and locked preferences in `session_cache.json` next to `GikiTransportShell.exe`, with automatic refresh/re-login on expiry.
- **Closed-Access Protection**: Pre-approved GIKI student accounts sign in directly (supporting short registration numbers like `2024297` → `u2024297@giki.edu.pk`); other accounts require Admin Approval.
- **Self-Updating Executable**: Checks GitHub Releases on startup, displays estimated update time, downloads in-place with a live progress bar, and auto-restarts into the latest version.

---

## Quick Start

1. Download **`GikiTransportShell.exe`** from the [Latest Release](https://github.com/misbah-ullah01/giki-transitpulse/releases/latest).
2. Place `GikiTransportShell.exe` in its own folder (it stores `session_cache.json` right beside the `.exe`).
3. Run `GikiTransportShell.exe` in **Windows Terminal** (recommended for full colors and clickable links).

---

## Keyboard Shortcuts

| Key | Action |
| --- | --- |
| `↑` / `↓` | Move selection |
| `←` / `→` | Switch category tabs |
| `Enter` | Confirm / View trip stops or ticket pass |
| `A` | Toggle `AUTO-FIRE ON/OFF` (when locked) |
| `B` | Book / Snipe locked tickets immediately |
| `U` | Release lock & return to setup |
| `T` | View Booked Tickets & Active Holds |
| `W` | Recharge Wallet (MWALLET) |
| `C` | Credits & Developer Info |
| `R` | Refresh data from server |
| `L` | Sign out / Switch account |
| `Q` / `Esc` | Quit / Back |

---

## Credits

Developed by **Misbah Ullah** — B.S. Computer Science, Batch 34 (3rd Year), GIKI  
GitHub: [https://github.com/misbah-ullah01](https://github.com/misbah-ullah01)
