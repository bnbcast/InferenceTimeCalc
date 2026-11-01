# Inference Time Calculator

Works out how many parallel AI attempts you need for at least one to fix a bug, with every step of the math shown. A probability explainer built in the browser.

## What it does

- Computes the number of attempts needed for a target success probability
- Shows every step of the formula: P(at least one success) = 1 − (1 − p)ⁿ
- SVG chart of success probability against attempt count
- Plain-language assumptions and interpretation

## Stack

JavaScript · Probability · Data viz · React 19 · Vite 6 · SVG

## Run locally

```sh
npm install
npm run dev
npm run build
```

## Deploy

GitHub Pages via GitHub Actions.
