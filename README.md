# SquadTime

**Plan complex workloads in seconds — without spreadsheets.**

SquadTime transforms raw workload hours into precise schedules, including start dates, end dates, end times, and a final deadline. It eliminates manual counting, reduces scheduling errors, and provides instant, reliable results directly in your browser.

---

## ✨ Features

* **Instant scheduling**

  * Convert workload hours into a full timeline in real time

* **Smart date handling**

  * Supports `dd/MM/yyyy`, `MMM d, yyyy`, and `YYYY-MM-DD`
  * Starts new schedules on the next Monday by default
  * Automatically skips weekends (optional)
  * Skips a custom list of holidays

* **Flexible workday configuration**

  * Define:

    * Start time
    * Optional break window (defaults to `12:00`–`14:00`)
    * End time

  Leave both break fields blank to schedule without a break.

* **Accurate time distribution**

  * Handles:

    * Breaks
    * Multi-day workloads
    * Overflow across working days

* **Spreadsheet-ready output**

  * Copy results in one click
  * Paste directly into Excel, Google Sheets, Notion, etc.

* **Schedule summary**

  * Review total workload, estimated span, final time, break impact, and the final deadline
  * The final deadline includes the date, time, and weekday

* **Auto-save**

  * Settings persist locally (no login required)

* **Internationalization**

  * English and Portuguese (auto-detected from user device)

* **Dark mode support**

  * Auto / Light / Dark themes

* **Privacy-first**

  * 100% client-side — no data leaves your browser

---

## 🧠 How It Works

1. Keep the default **start date** (the next Monday) or enter another date
2. Paste your **workload hours** (one per line or separated by space/comma)
3. Configure your **working hours** and optional break
4. Add any **holidays** to skip
5. Click **Generate Schedule**

You’ll instantly get:

* Start date per task
* End date per task
* End time per task
* Final deadline with date, time, and weekday

---

## 📋 Example

**Input:**

```
Start date: Jul 27, 2026

Workload:
4
8
12
6
```

**Output:**

```
Start Dates:
May 11, 2026
May 11, 2026
May 12, 2026
...

End Dates:
May 11, 2026
May 12, 2026
...

End Times:
12:00
18:00
...
```

---

## ⚙️ Configuration

You can customize:

* **Working hours**

  * Day start
  * Optional break start and end
  * Day end

* **Weekend handling**

  * Skip or include weekends

* **Holidays**

  * Select a date and leave the field to add it to the list
  * Remove a holiday individually with the `×` action
  * Holidays are skipped even when weekend skipping is disabled

* **Language**

  * Auto-detected (can be overridden)

* **Theme**

  * Auto / Light / Dark

---

## 📦 Tech Stack

* Vanilla JavaScript (no frameworks)
* HTML5 + CSS3
* LocalStorage for persistence

No dependencies. No build step. Just open and use.

---

## 🚀 Getting Started

### Option 1 — Run locally

```bash
git clone <your-repo>
cd squadtime
open index.html
```

### Option 2 — Deploy

You can deploy instantly on:

* Vercel
* Netlify
* GitHub Pages
* AWS Amplify

---

## 🧭 Roadmap (Ideas)

* Export to Github Projects

---

## 🔐 Privacy

SquadTime is fully client-side:

* No tracking
* No data collection
* No external requests

Your data stays in your browser.

---

## 👨‍💻 Author

Built by [argolo.dev](https://argolo.dev)

---

## 💡 Positioning

SquadTime is designed for:

* Developers
* Product Managers
* Operations teams
* Anyone tired of using spreadsheets for scheduling
