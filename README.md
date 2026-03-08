# Lightning x AI — The Machine-Payable Web

A single-page interactive explainer demonstrating how the **L402 protocol** turns the **Bitcoin Lightning Network** into the payment layer for autonomous AI agents.

## What Is This?

This project is an educational website that explores the intersection of Lightning Network micropayments and AI agent autonomy. It covers:

- **The Problem** — Why AI agents can think but can't pay (identity bottlenecks, micropayment failures, speed mismatches, and global friction)
- **The Solution** — How the L402 protocol combines HTTP 402 status codes, Lightning invoices, and macaroon-based credentials to let machines pay machines
- **Old vs New** — A comparison of traditional payment rails against L402 + Lightning for AI use cases
- **Ecosystem Overview** — Key projects building in this space (Lightning Labs Agent Tools, LightningProx, lnget, Aperture, x402, Scoped Macaroons)
- **Interactive Demo** — A simulated terminal showing an AI agent purchasing API inference with Lightning — no signup, no API key, just sats

## Features

- Animated hero section with gradient backgrounds
- Step-by-step L402 flow visualizer with auto-play
- Animated counter stats (HTTP 402 responses, Lightning wallets, monthly transactions)
- Side-by-side comparison table (Traditional vs L402 + Lightning)
- Simulated terminal demo of an agent paying for Claude API access via Lightning
- Fully responsive design
- No external JavaScript dependencies — pure HTML, CSS, and vanilla JS

## Getting Started

Open `index.html` in any modern web browser:

```bash
# Clone the repository
git clone https://github.com/hasky00/lightningAI.git
cd lightningAI

# Open in your default browser
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

No build tools, bundlers, or servers required.

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, grid, flexbox, animations, gradients
- **Vanilla JavaScript** — Intersection Observer API, DOM manipulation, animation sequencing

## License

This project is open source. Feel free to use and modify for educational purposes.
