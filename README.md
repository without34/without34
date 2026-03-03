## Hi, I'm Claire 👋

Senior Software Engineer building an automated US stock trading system.

---

## PB Trading System

An end-to-end algorithmic trading platform focused on US equities and leveraged ETFs.

Modular architecture:

Market Data → Indicator Engine → Signal Engine → Risk Control → Order Execution → Portfolio Tracking

---

## Architecture & Tech Stack

Core execution engine:
- C# multithreaded trading engine
- Deterministic order execution logic
- IBKR API integration

Infrastructure:
- PostgreSQL for structured historical and live trading data
- Docker-based containerized services
- Kubernetes orchestration

Research layer:
- Python for strategy research and statistical analysis

Previous architecture:
- Python + WebSocket real-time processing
- Node.js-based web dashboard

Migrated to a C# multithreaded engine to reduce latency and improve execution stability.

---

## Trading Workspace UI

The platform includes a dedicated desktop trading workspace with:

- Real-time candlestick chart with technical indicators
- Order book and microstructure view
- Order activity panel
- Account summary and asset information
- Open positions tracking
- System log and trading log
- Strategy signal display
- Profit and risk adjustment controls

The interface is designed for low-latency monitoring and deterministic trade control.

---

## Implemented

- Intraday trading engine
- Momentum breakout and pullback strategies
- RSI and trend alignment filters
- Volume confirmation logic
- Automated trailing stop management
- Bracket order execution
- Backtesting framework
- Portfolio performance tracking

---

## Currently Working On

- Minor stability fixes in the day trading strategy
- Structured data aggregation into PostgreSQL
- Improving signal evaluation reliability

---

## Next Phase

- Swing trading strategy implementation
- Symbol-level data collection including volume, liquidity, and price structure
- Liquidity and volume analysis layer
- Entry timing refinement based on statistical evaluation
- 2–3 month extended backtesting validation period
- Development of a dedicated internal analysis tool

---

## PB Trading Workspace
<img width="1911" height="1028" alt="Screenshot 2026-03-03 110623" src="https://github.com/user-attachments/assets/7f6c2f7b-a169-4dab-b507-2bb9865e6c37" />

### Trading Workspace
![Workspace](images/workspace.png)

---

Independent quant development project.  
Codebase is private.
