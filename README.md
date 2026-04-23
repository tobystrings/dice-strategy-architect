# 🎲 Dice Strategy Architect

**Design • Simulate • Export** professional dice betting strategies for crypto casinos and dice games.

A powerful, browser-based tool to build custom auto-betting rules, backtest them with Monte Carlo simulations, and export ready-to-use `dobet()` JavaScript snippets for platforms like Stake, CryptoGames, Rollbit, and other dice sites that support custom scripts.

![Demo](https://via.placeholder.com/800x400/0a0c10/238636?text=Dice+Strategy+Architect+Demo) <!-- Replace with actual screenshot later -->

## ✨ Features

- **Visual Rule Builder**: Intuitive UI to create complex conditional strategies (Martingale, reverse, streaks, resets, stop conditions, etc.)
- **Realistic Monte Carlo Simulator**: Run thousands of simulations with configurable house edge, starting balance, base bet & chance
- **Live Statistics**: Avg profit, win rate, bust rate, and more
- **One-Click Exports**:
  - Strategy as JSON (importable)
  - Full `dobet()` script ready for casino auto-bet engines
- **Preset Strategies**: Load popular systems instantly (Martingale, Anti-Martingale, D'Alembert, etc.)
- **Sample Run Visualization**: See balance progression chart for a single simulated run
- **Fully Client-Side**: No backend, works offline, perfect for GitHub Pages

## 🚀 Quick Start

### Run Locally (Recommended for Development)

```bash
git clone https://github.com/YOUR_USERNAME/dice-strategy-architect.git
cd dice-strategy-architect
# Option 1: Just open in browser
open index.html   # or double-click

# Option 2: With local server (recommended)
npm install
npm start
# Then visit http://localhost:3000
