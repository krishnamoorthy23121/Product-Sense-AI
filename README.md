# 🧠 Product-Sense-AI

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-brightgreen.svg)](https://www.python.org/downloads/)
[![AI-Product-Management](https://img.shields.io/badge/Focus-AI--Product--Mgmt-orange.svg)]()
[![Strategic-AI](https://img.shields.io/badge/Field-Strategic--AI-red.svg)]()

**Product-Sense-AI** is an autonomous framework designed to augment and scale Product Management capabilities using Generative AI. It processes high-volume market signals, user feedback, and competitive intelligence to generate data-driven product strategies, prioritized roadmaps, and comprehensive PRDs.

---

## 🚀 Key Features

- **🎯 Autonomous Product Strategist:** An agentic engine that deconstructs raw market data into actionable product objectives.
- **🔄 Strategy-to-Roadmap Loop:** Automatically translates high-level strategic goals into prioritized feature sets.
- **📊 Sentiment-Driven Prioritization:** Integrated NLP modules to weigh user feedback based on emotional impact and frequency.
- **🛠️ Automated PRD Generation:** Create production-ready Product Requirement Documents from a single strategic prompt.
- **🧪 Strategy Simulation:** Test multiple strategic directions against simulated market responses.

---

## 🏗️ Architecture

`mermaid
graph TD
    A[Market Signals / User Feedback] --> B[Data Ingestion Layer]
    B --> C[NLP Perception Engine]
    C --> D{AI Strategist Agent}
    D --> E[Prioritized Backlog]
    D --> F[Automated PRDs]
    D --> G[Strategic Roadmap]
    E --> H[Product Feedback Loop]
    G --> H
    H --> A
`

---

## 🛠️ Project Structure

`	ext
Product-Sense-AI/
├── src/
│   ├── agents/         # AI Strategist and PRD agents
│   ├── perception/     # NLP and Sentiment Analysis logic
│   ├── roadmapping/    # Prioritization and visualization logic
│   └── templates/      # Standardized PRD and Strategy templates
├── notebooks/          # Market analysis simulations
├── tests/              # Comprehensive evaluation suite
└── requirements.txt    # Project dependencies
`

---

## 📖 Quick Start

`python
from src.agents.strategist import AIProductStrategist, MarketSignal

# 1. Initialize the Strategist
pm_bot = AIProductStrategist(name="Visionary-PM")

# 2. Input market signals
signals = [
    MarketSignal(source="AppStore", content="Login is too slow", sentiment=-0.8),
    MarketSignal(source="Competitor", content="Competitor X launched AI summaries", sentiment=0.5)
]

# 3. Generate Strategy
plan = pm_bot.analyze_signals(signals)

for item in plan:
    print(f"[{item.priority}] {item.objective}")
`

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
<p align="center">Built with ❤️ by <a href="https://github.com/Salset0">Harinath Krishnamoorthy</a></p>