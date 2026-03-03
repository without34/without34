## Hi, I'm Claire 👋

Senior Software Engineer with 15+ years of experience building real-time distributed backend systems.

My primary background is in large-scale game server architecture and AWS-based cloud services at Amazon.  
I have worked extensively on multi-threaded C/C++ server engines, network protocols (UDP/TCP), concurrency control, and scalable cloud infrastructure.

I enjoy entering new technical domains and building systems from first principles.  
Having worked across C/C++, C#, Java, Scala, Python, and Node.js, I focus on core system design principles rather than being attached to specific tools.

Currently, I am applying real-time backend engineering expertise to financial automation.

---

# PB Trading System

An automated US stock trading platform designed with the same engineering principles used in large-scale online game servers:

- Deterministic behavior under concurrency
- Event-driven architecture
- Strict latency awareness
- Risk-aware execution logic
- Stateful system consistency

Architecture flow:

Market Data → Indicator Engine → Signal Engine → Risk Control → Order Execution → Portfolio Tracking

<img width="1911" height="1028" alt="Screenshot 2026-03-03 110623" src="https://github.com/user-attachments/assets/05a75d9d-bbf9-4dde-9903-1022b9b8b5c7" />


---

# Architecture & Tech Stack

## Execution Engine
- C# multithreaded trading core
- Deterministic order routing logic
- IBKR API integration
- Real-time candle and indicator processing

## Infrastructure
- PostgreSQL for structured historical and live data storage
- Docker containerization
- Kubernetes orchestration
- AWS-based service architecture background

## Research & Analytics
- Python for statistical modeling and backtesting
- Structured strategy validation framework

The system was initially built using Python + WebSocket with a Node.js-based frontend,  
and later migrated to a C# multithreaded engine to improve latency, responsiveness, and execution stability.

---

# Trading Workspace

A dedicated desktop trading environment designed for live execution monitoring and operational control.

Key components:

- Multi-timeframe candlestick chart with technical indicators
- Strategy signal markers plotted directly on chart
- Real-time order activity tracking
- Account summary including balance and buying power
- Position monitoring with live PnL
- System and trading logs for execution traceability
- Strategy signal visibility and state tracking
- Manual profit and risk adjustment controls

The workspace is built not just for visualization, but for deterministic monitoring of signal state, execution flow, and portfolio consistency under live market conditions.

---

# Implemented

- Intraday trading engine
- Momentum breakout and pullback strategies
- RSI and trend alignment filters
- Volume confirmation logic
- Automated trailing stop management
- Bracket order execution
- Structured backtesting framework
- Portfolio performance tracking

---

# Currently Working On

- Stability improvements and edge-case handling in day trading strategies
- Structured data aggregation and normalization into PostgreSQL
- Signal validation reliability improvements
- Enhanced execution logging for traceability

---

# Next Phase

- Swing trading strategy implementation
- Symbol-level liquidity and volume profiling
- Price structure and volatility pattern analysis
- Entry timing refinement through statistical evaluation
- 2–3 month extended structured backtesting validation
- Development of a dedicated internal analysis tool for performance diagnostics
- Adaptive risk model improvements
- Execution monitoring under high-volatility conditions

The long-term objective is to evolve this into a research-driven, data-informed trading architecture rather than a fixed-rule strategy engine.

---

# Screenshots

### Live Trading Workspace
<img src="images/workspace.png" width="900" />

---

Independent quant development project.  
Codebase is private.
