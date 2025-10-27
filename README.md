# Working Hours Indicator

A tiny, zero-dependency web app that visualizes your workday as a **circular progress** clock. Track when you arrived, see how much time has passed, and how much remains until the end of the day — updated every second.

**Live demo:** https://grobakh.github.io/wh/  
**Repository:** https://github.com/grobakh/wh

---

## Features

- ⏱️ **Circular progress** of the workday (elapsed vs remaining)
- 🕙 **Configurable work hours** (start → end)
- ✅ Quick actions: **“Arrived now”**, **“Reset”**, manual set of arrival/leave time
- 🔔 Milestones: **¼**, **½**, **¾** passed markers
- 🌍 Uses **browser time zone**
- ⚡ **No build, no backend** — just open `index.html`

> Language: UI currently in Russian.

---

## Quick Start

1. Clone or download the repo.
2. Open `index.html` in any modern browser.
3. Set your arrival time or click **“Сейчас пришёл”** (Arrived now).
4. Optionally adjust **Рабочий день** (workday start → end).

That’s it. The ring will tick in real time.

---

## Configuration

- **Work hours:** Set directly in the UI (e.g., `10:00 → 18:00`).
- **Arrival / Leave:**  
  - Click **“Пришёл”** or **“Уйду”** to set manually.  
  - Click **“Сейчас пришёл”** to set arrival to the current time.  
  - Click **“Сбросить”** to clear times.

---

## Development

This project is plain HTML (with inline CSS/JS). No toolchain required.

- Open `index.html` locally, or
- Serve via any static server (optional), e.g.:
  ```bash
  python3 -m http.server 5173
