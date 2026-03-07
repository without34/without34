## Hi, I'm Claire 👋

Senior Software Engineer with 15+ years of experience building real-time distributed backend systems.

My primary background is in large-scale game server architecture and AWS-based cloud services at Amazon.  
I have worked extensively on multi-threaded C/C++ server engines, network protocols (UDP/TCP), concurrency control, and scalable cloud infrastructure.

I enjoy entering new technical domains and building systems from first principles.  
Having worked across C/C++, C#, Java, Scala, Python, and Node.js, I focus on core system design principles rather than being attached to specific tools.

Currently, I am applying real-time backend engineering expertise to financial automation.

---

# PB Trading System

An automated US stock trading platform designed with a strong focus on reliability, system structure, and maintainability.

<img width="1911" height="1028" alt="Screenshot 2026-03-03 110623" src="https://github.com/user-attachments/assets/05a75d9d-bbf9-4dde-9903-1022b9b8b5c7" />


---

# Architecture & Tech Stack

## Execution Engine
- C# multi-threaded trading core
- Deterministic order logic
- IBKR API integration
- Real-time candle, indicator and orderbook processing
- Prediction system
- Evaluation system
- Risk management
  

## Real-time UI Engine 
- Cabdle chart and indicator
- Signal panel
- Orderbook
- Order management
- Asset management
- Update TP and SL
- Update strategy parameters
- Logging

## Infrastructure
- PostgreSQL for structured historical and live data storage
- Docker containerization
- Kubernetes orchestration

## Analytics and Test
- Analysis Tool with data
- Mock test
- Backtesting(WIP)

The system was initially built using Python + WebSocket with a Node.js-based frontend,  
and later migrated to a C# multithreaded engine to improve latency, responsiveness, and execution stability.

--

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


Independent quant development project.  
Codebase is private.
