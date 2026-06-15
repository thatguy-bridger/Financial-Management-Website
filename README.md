# 💰 MyFinances — Personal Finance Dashboard

A self-contained personal finance web app. All data lives in your browser. Nothing is ever sent to a server.

## Features

- **Dashboard** — Net position, monthly overview, category spending, recent transactions, investment snapshot
- **Transactions** — Log spending, rewards, extra income with search, filters, and category tagging
- **Income** — Paycheck records with gross/tax/net, monthly summaries, tithing calculation
- **Investing** — Stock positions with buy price, current price, gain/loss, % change
- **Timesheets** — Weekly hours log with automatic gross/net estimates from your hourly rate
- **Settings** — Theme toggle, accent color, hourly rate, tax %, tithing %, custom categories, currency, import/export

---

## Deploy to GitHub Pages (Free Hosting, 5 min)

### Step 1 — Create a GitHub account
Sign up free at **github.com** if you don't have one.

### Step 2 — Create a new repository
- Click **+** → **New repository**
- Name: `my-finances` (or anything)
- Visibility: **Public** (required for free Pages)
- Click **Create repository**

### Step 3 — Upload index.html
- Click **Add file** → **Upload files**
- Drop `index.html` in
- Click **Commit changes**

### Step 4 — Enable GitHub Pages
- Go to **Settings** → **Pages**
- Source: `Deploy from a branch`
- Branch: `main`, Folder: `/(root)`
- Click **Save**

### Step 5 — Visit your site
After ~2 minutes your app is live at:
```
https://YOUR-USERNAME.github.io/my-finances
```

---

## Add to Phone Home Screen (works like a native app)

**iPhone / Safari:**
1. Open your URL in Safari
2. Tap Share → **Add to Home Screen**

**Android / Chrome:**
1. Open in Chrome
2. Menu (⋮) → **Add to Home Screen**

---

## Data & Privacy

- All data is in your **browser's localStorage** — never leaves your device
- **Export** (Settings or ⬇️ nav button) → downloads a JSON backup
- **Import** → restores from backup or lets you move between devices
- Clearing browser storage deletes your data; always keep a backup export

---

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl/Cmd + K` | Cycle through pages |
| `Escape` | Close open modal |

---

## Settings You Can Customize (no code required)

| Setting | What it does |
|---|---|
| Dark / Light mode | Theme toggle |
| Accent color | 5 color options |
| Hourly rate | Used for timesheet estimates |
| Tax rate % | Gross → net on timesheets |
| Tithing rate % | Auto-calculates from income |
| Currency symbol | $, €, £, ¥ |
| Categories | Add / remove spending categories |
