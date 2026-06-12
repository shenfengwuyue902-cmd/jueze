# Jueze ? Decision Matrix Tool

Turn every important decision into a quantifiable choice.

A lightweight online decision matrix tool that helps you systematically compare multiple options and make rational decisions.

---

## What Is This

**Decision paralysis** is a common struggle when facing multiple options.

**Jueze** turns the decision process into a quantifiable matrix:
1. Define evaluation criteria with weights
2. List all options to compare
3. Score each option against each criterion
4. Get weighted scores, rankings, and charts automatically

## Usage

Open `index.html` in any browser. No installation or server required.

## Features

- **Zero dependencies** ? Single HTML file, just open and use
- **Persistent data** ? Auto-saved to localStorage
- **Dark/Light theme** ? Matches system preference or toggle manually
- **Score color feedback** ? Green (high), amber (mid), orange (low)
- **Progress bars** ? Visual comparison of scores in rankings
- **Reordering** ? Move criteria and options up/down
- **Interactive step navigation** ? Click to jump between sections
- **Statistics overview** ? Highest, lowest, and score gap at a glance
- **Export/Import** ? JSON format for backup and restore
- **Copy results** ? Formatted text for sharing
- **Responsive design** ? Works on mobile, tablet, and desktop

## Use Cases

| Scenario | Example |
|----------|---------|
| Shopping | Compare different products |
| Job search | Evaluate job offers |
| Education | Compare schools or programs |
| Planning | Prioritize project tasks |
| Life decisions | Rentals, cars, insurance plans |

## Tech Stack

- Pure HTML + CSS + JavaScript
- Canvas 2D API for bar charts
- localStorage for persistence
- ~35KB total

## Deployment

### Option 1: Direct
Double-click `index.html` to open in browser.

### Option 2: GitHub Pages
```bash
git clone https://github.com/<your-username>/jueze.git
cd jueze
git push origin main
```
Enable Pages in repo Settings.

### Option 3: Vercel / Netlify
Drag and drop `index.html` onto Vercel or Netlify.

## License

MIT
