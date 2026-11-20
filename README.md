<p align="center">
  <a href="https://github.com/misbah-ullah01/giki-transitpulse/releases/latest">
    <img src="https://github.com/user-attachments/assets/8d0db23e-46e6-4187-a0a9-298cc8df1510" alt="Stride Logo" width="110" />
  </a>
</p>

<h1 align="center">Stride</h1>

<p align="center">
  Fast, closed-access terminal shell for <strong>GIKI Transport</strong>: automated opening-time booking, MWALLET recharge, and built-in updates.
</p>

<p align="center">
  <a href="https://github.com/misbah-ullah01/giki-transitpulse/releases/latest">
    <img src="https://img.shields.io/badge/Download-stride.exe-0A0F1E?style=for-the-badge" alt="Download stride.exe" />
  </a>
  <img src="https://img.shields.io/badge/Platform-Windows-1E293B?style=for-the-badge" alt="Windows" />
</p>

> **Private Release Distribution**: This repository hosts compiled `.exe` releases only. Source code is not published here.

---

## Features

- **Auto-Fire Ticket Sniper**: Lock your **City**, **Direction** (`Inbound` / `Outbound` / `Both`), **Stops**, and **Departure Times**. At opening time, `Stride` pre-warms your session, burst-polls availability, and fires parallel holds + confirmation automatically.
- **Zero-Flicker Terminal UI**: Double-buffered ANSI interface with live 1-second PKT countdowns and bordered ticket cards.
- **Booked Tickets & Pass**: View confirmed student tickets (`[T]`) with `#ticket_code`, stops, PKT departure time, and full-screen boarding pass details.
- **MWALLET Recharge**: Top up G-Bux directly (`[W]`) with live limit checking and JazzCash confirmation support.
- **Persistent Local Session**: Saves tokens, cookies, and locked preferences in `session_cache.json` next to `stride.exe` for instant auto-relogin.
- **Self-Updating Executable**: Checks GitHub Releases on startup, shows estimated update time, downloads in-place, and auto-restarts.

---

## Quick Start

1. Download **`stride.exe`** from the [Latest Release](https://github.com/misbah-ullah01/giki-transitpulse/releases/latest).
2. Place `stride.exe` in its own folder (`session_cache.json` is stored next to it).
3. Run `stride.exe` in **Windows Terminal** (recommended for full colors and clickable links).

---

## Controls

| Key | Action |
| --- | --- |
| `↑` / `↓` | Move selection |
| `←` / `→` | Switch category tabs |
| `Enter` | Confirm / View details |
| `A` | Toggle `AUTO-FIRE ON/OFF` |
| `B` | Book / Snipe locked tickets now |
| `U` | Release lock |
| `T` | Booked Tickets & Holds |
| `W` | Recharge Wallet (MWALLET) |
| `C` | Credits |
| `R` | Refresh |
| `L` | Logout |
| `Q` / `Esc` | Quit / Back |

---

<p align="center">
  Built by <strong>Misbah Ullah</strong> · CS Batch 34, GIKI<br/>
  <a href="https://github.com/misbah-ullah01">github.com/misbah-ullah01</a>
</p>
