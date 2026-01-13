# 🔴 Red Queen AI - Self-Learning Vision-Based Trading System

> *"You have to run as fast as you can just to stay in the same place. If you want to get somewhere else, you must run at least twice as fast as that."*

**Red Queen AI** is a next-generation trading dashboard concept that fuses traditional technical analysis (Pine Script logic) with computer vision (screen analysis) and evolutionary game theory. It features a futuristic, responsive "Bento Grid" interface designed for high-frequency decision-making.

---

## ⚡ Core Systems

### 1. 🧠 Neural Interface (UI/UX)
- **Responsive Bento Grid:** Auto-arranging, snap-to-edge dashboard layout using CSS Grid.
- **Glassmorphism & CRT Effects:** Cyberpunk aesthetic with real-time blur and scanline shaders.
- **Dynamic Charting:** Integrated Recharts visualization overlaying trade executions on price action.

### 2. 👁️ Computer Vision Bridge
- **Screen Capture API:** Captures live video frames from the user's screen (e.g., TradingView charts).
- **Pixel Analysis:** Analyzes color dominance (Green vs. Red candles) to generate a secondary "Vision Signal".
- **Signal Alignment:** Fuses API data signals with visual confirmation to filter false positives.

### 3. 🧬 Evolutionary Engine
- **Weight Adaptation:** Dynamically shifts trust between "Pine Script" (Math) and "Vision" (Eyes) based on recent win rates.
- **Regime Detection:** Classifies market states (Trending, Ranging, Volatile, Compression) using statistical variance.
- **Genetic Logging:** Tracks evolution events where the system alters its own confidence thresholds.

### 4. ⚖️ Risk Physics
- **Real Slippage Simulation:** Calculates estimated slippage based on live order book depth simulation.
- **Fee Modeling:** Accounts for Maker/Taker fees in PnL calculations.
- **Kill Zone Logic:** Automatically vetoes trades during "Compression" regimes to prevent chop.

---

## 🚀 Quick Start

### Prerequisites
- Node.js & npm/yarn
- A modern browser (Chrome/Edge recommended for Screen Capture API support)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-org/red-queen-ai.git
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the simulation**
   ```bash
   npm run dev
   ```

---

## 🎮 Usage Guide

1. **Select Vision Source:**
   - Go to `System Config` -> `General`.
   - Toggle between **API DATA FEED** (Pure Math) and **SCREEN CAPTURE** (Visual Analysis).
   - If Screen Capture is selected, grant browser permission to share your chart window.

2. **Monitor Regimes:**
   - Watch the **Regime Matrix**. Avoid trading manually when the "COMPRESSION" (Kill Zone) warning is active.

3. **Manual Override:**
   - Use the **Manual Operations** panel to execute trades if the AI is hesitant.
   - The AI will still track and log your manual trades in the history.

4. **Evolution:**
   - Observe the **Neural Alignment** panel. As the system trades, it will adjust the `Pine` vs `Vision` weights.
   - If one strategy fails repeatedly, the Red Queen minimizes its influence.

---

## 🛠️ Tech Stack

- **Frontend:** React 18, TypeScript, Vite
- **Styling:** Tailwind CSS, Lucide React (Icons)
- **Visualization:** Recharts
- **State Management:** React Hooks (Custom Simulation Engine)
- **Data:** WebSocket (Binance Public Streams for Demo)

---

**Disclaimer:** *This software is a simulation and visualization tool. It does not execute real financial transactions by default. Use "LIVE API" mode at your own risk.*
