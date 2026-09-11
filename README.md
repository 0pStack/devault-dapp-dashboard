# DeVault — dApp Dashboard (UI Demo)

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)
![Ethereum](https://img.shields.io/badge/-Ethereum-3C3C3D?logo=ethereum&logoColor=white)
![Web3](https://img.shields.io/badge/-Web3-F16822?logo=web3dotjs&logoColor=white)
[![Stars](https://img.shields.io/github/stars/0pStack/devault-dapp-dashboard?style=flat)](https://github.com/0pStack/devault-dapp-dashboard/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/0pStack/devault-dapp-dashboard)](https://github.com/0pStack/devault-dapp-dashboard/commits/main)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

A responsive **HTML & CSS-only** demo of a dashboard UI for a decentralized application (dApp). There is no JavaScript and no real blockchain integration — this project focuses purely on layout, styling, accessibility, and visual presentation using dummy data.

![DeVault dashboard demo](screenshots/demo1.png)

## About

DeVault is a UI mockup for a fictional decentralized wallet. It demonstrates how a clean, accessible dashboard can be built using only semantic HTML and modern CSS. All wallet balances, transactions, and network details shown in the interface are static placeholder values.

## Features

- **Responsive layout** — adapts from mobile and tablet up through desktop and ultra-wide screens
- **Branded header** — inline SVG logo with anchor navigation (Wallet, Transactions, Create)
- **Wallet section** — current balance card, asset list, network info, and a pure-CSS 7-day trend indicator
- **Transactions table** — styled table with alternating rows, hover states, and status pills (confirmed, pending, failed)
- **Create transaction form** — UI-only form with multiple field types (text, select, number, datetime-local, textarea) and clear focus styles
- **Dark / light mode** — automatic via `prefers-color-scheme`
- **Accessibility** — semantic landmarks (`header`, `main`, `footer`, `section`), skip link, ARIA labels, visible focus states, and proper form labels
- **Custom typography** — Inter and Playfair Display via Google Fonts

## Tech Stack

- **HTML5** — semantic markup with ARIA attributes
- **CSS3** — custom properties, grid, flexbox, media queries, `prefers-color-scheme`
- **Google Fonts** — Inter and Playfair Display
- **Inline SVG** — for the logo

No build tools, no frameworks, no JavaScript.

## How to View

Clone the repo and open `index.html` directly in any modern browser:

```bash
git clone https://github.com/0pStack/devault-dapp-dashboard.git
cd devault-dapp-dashboard
```

Then either double-click `index.html` or serve the folder with any static file server, for example:

```bash
# Python 3
python -m http.server 8000

# Node.js (with npx)
npx serve .
```

Then visit `http://localhost:8000`.

## Project Structure

```
devault-dapp-dashboard/
├── index.html        # Markup for the dashboard
├── styles.css        # All styling (responsive, theming, components)
├── screenshots/      # Preview images used in the README
│   └── demo1.png
└── README.md
```

## Screenshots

![Dashboard overview](screenshots/demo1.png)

## License

This project is provided as a UI demo for learning and portfolio purposes.