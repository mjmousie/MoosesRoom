# Moose's Room

A mobile-first card game app featuring three casino-style games built with React, TypeScript, and Vite.

## Games

### Midnight Baseball
A poker-style game where you bet on the Player hand or the Widow (Banker). Face the Dealer with optional wagers on wild cards and bonus cards. 1:1 payout.

### Iron Cross
Each player receives 5 cards plus a shared cross-shaped board (5 community cards arranged in a + pattern). Choose a row — vertical, horizontal, or mystery — back up your bet, and battle the Dealer. Supports a separate bonus bet.

### Hi/Lo
Predict whether the next card drawn will be higher or lower than the current card. Build a streak to climb a multiplier ladder up to 25x. Cash out at any time or go for the full 7-in-a-row jackpot. Live probability hints show your odds on each guess.

## Tech Stack

- **React 19** + **TypeScript** — component architecture and type safety
- **Vite** — fast dev server and build tooling
- **Tailwind CSS** — utility-first styling
- **Framer Motion** — card animations (drop, flip, slide, shake, confetti)
- **Zustand** — global balance and per-game state stores

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Build

```bash
npm run build
```

Output lands in `dist/`.
