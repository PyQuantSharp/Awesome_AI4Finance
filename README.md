# Awesome AI for Finance [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/Awesome_AI4Finance?style=social)](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance)
[![License](https://img.shields.io/github/license/AI4Finance-Foundation/Awesome_AI4Finance)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance/pulls)

> A curated list of awesome AI / machine learning / deep learning / reinforcement learning / LLM tools, frameworks, and resources for quantitative finance.

This list is maintained by the [AI4Finance Foundation](https://github.com/AI4Finance-Foundation). If you find it useful, please give it a star!

---

## Contents

- [AI4Finance Foundation Ecosystem](#ai4finance-foundation-ecosystem)
- [LLMs for Finance](#llms-for-finance)
- [AI Agents for Finance](#ai-agents-for-finance)
- [Deep Reinforcement Learning](#deep-reinforcement-learning)
- [Machine Learning](#machine-learning)
- [Quantitative Trading & Backtesting](#quantitative-trading--backtesting)
- [Data Sources](#data-sources)
- [Technical Analysis](#technical-analysis)
- [Portfolio Management & Risk](#portfolio-management--risk)
- [Sentiment Analysis & NLP](#sentiment-analysis--nlp)
- [Trading Platforms](#trading-platforms)
- [Visualization & Rendering](#visualization--rendering)
- [High Performance Computing](#high-performance-computing)
- [Research Papers & Surveys](#research-papers--surveys)
- [Books](#books)
- [Contributing](#contributing)

---

## AI4Finance Foundation Ecosystem

The [AI4Finance Foundation](https://github.com/AI4Finance-Foundation) provides a full-stack open-source ecosystem for AI-driven finance, from data to deployment.

| Project | Stars | Description |
|---------|-------|-------------|
| [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinGPT?style=flat-square) | Open-source financial large language models. Fine-tuning LLMs (LLaMA, ChatGLM, etc.) with financial data for sentiment analysis, robo-advising, and quantitative trading. |
| [FinRL](https://github.com/AI4Finance-Foundation/FinRL) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL?style=flat-square) | The first open-source framework for financial reinforcement learning. Full pipeline from data processing to DRL-based trading (stock, crypto, forex). |
| [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRobot?style=flat-square) | Open-source AI agent platform for financial analysis using LLMs. Multi-agent architecture for report generation, analysis, and trading decisions. |
| [ElegantRL](https://github.com/AI4Finance-Foundation/ElegantRL) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/ElegantRL?style=flat-square) | Scalable and elastic deep reinforcement learning library using PyTorch. Lightweight, efficient, and cloud-native. |
| [FinRL-Trading](https://github.com/AI4Finance-Foundation/FinRL-Trading) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Trading?style=flat-square) | Deep Reinforcement Learning for Automated Stock Trading: An Ensemble Strategy (ICAIF 2020). |
| [FinRL-Meta](https://github.com/AI4Finance-Foundation/FinRL-Meta) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Meta?style=flat-square) | A universe of dynamic market environments for financial reinforcement learning. Standardized datasets for stock, crypto, and forex. |
| [FinNLP](https://github.com/AI4Finance-Foundation/FinNLP) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinNLP?style=flat-square) | Democratizing internet-scale financial data. NLP toolkit for financial news and social media data processing. |
| [FinRL-Tutorials](https://github.com/AI4Finance-Foundation/FinRL-Tutorials) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Tutorials?style=flat-square) | Jupyter notebook tutorials covering stock trading, portfolio allocation, crypto trading, and more. |
| [FinRL-Podracer](https://github.com/AI4Finance-Foundation/FinRL_Podracer) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL_Podracer?style=flat-square) | Cloud-based framework for massively parallel financial RL training. |
| [RLSolver](https://github.com/AI4Finance-Foundation/RLSolver) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/RLSolver?style=flat-square) | RL-based solver for combinatorial optimization problems in finance. |

---

## LLMs for Finance

Large Language Models are transforming finance through automated analysis, report generation, and intelligent trading.

| Project | Stars | Description |
|---------|-------|-------------|
| [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinGPT?style=flat-square) | Open-source financial LLM framework with LoRA/QLoRA fine-tuning on financial data. |
| [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRobot?style=flat-square) | AI agent platform for financial analysis using LLMs with multi-agent architecture. |
| [FinBERT](https://github.com/ProsusAI/finBERT) | ![Stars](https://img.shields.io/github/stars/ProsusAI/finBERT?style=flat-square) | Pre-trained NLP model to analyze sentiment of financial text. Built on BERT, fine-tuned on financial corpus. |
| [FinNLP](https://github.com/AI4Finance-Foundation/FinNLP) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinNLP?style=flat-square) | Toolkit for financial NLP with easy access to financial news and social media data. |
| [XuanYuan](https://github.com/Duxiaoman-DI/XuanYuan) | ![Stars](https://img.shields.io/github/stars/Duxiaoman-DI/XuanYuan?style=flat-square) | Chinese financial chat LLM from Du Xiaoman Financial. Hundreds of billions of parameters, fine-tuned on financial domain data. |
| [DISC-FinLLM](https://github.com/FudanDISC/DISC-FinLLM) | ![Stars](https://img.shields.io/github/stars/FudanDISC/DISC-FinLLM?style=flat-square) | Chinese financial LLM from Fudan University. Multi-expert fine-tuning for QA, domain NLP, math computation, and RAG-based consulting. |
| [PIXIU (FinMA)](https://github.com/The-FinAI/PIXIU) | ![Stars](https://img.shields.io/github/stars/The-FinAI/PIXIU?style=flat-square) | Open-source financial LLM evaluation framework with FinMA models (7B/30B), FinBen benchmark, and 136K instruction-tuning dataset. |
| [Fin-R1](https://github.com/SUFE-AIFLM-Lab/Fin-R1) | ![Stars](https://img.shields.io/github/stars/SUFE-AIFLM-Lab/Fin-R1?style=flat-square) | Financial reasoning LLM based on Qwen2.5-7B, trained with SFT + RL on 60K chain-of-thought samples. SOTA on FinQA and ConvFinQA. |
| [InvestLM](https://github.com/AbaciNLP/InvestLM) | ![Stars](https://img.shields.io/github/stars/AbaciNLP/InvestLM?style=flat-square) | Investment-focused LLM fine-tuned on LLaMA-65B using CFA exams, SEC filings, and quant finance data. Rated comparable to GPT-4 by hedge fund managers. |

---

## AI Agents for Finance

Autonomous AI agents that can analyze markets, make trading decisions, and generate financial reports.

| Project | Stars | Description |
|---------|-------|-------------|
| [TradingAgents](https://github.com/TauricResearch/TradingAgents) | ![Stars](https://img.shields.io/github/stars/TauricResearch/TradingAgents?style=flat-square) | Multi-agent LLM financial trading framework. Specialized agents (fundamentals, sentiment, technical) debate and reach consensus on trades. |
| [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRobot?style=flat-square) | Open-source AI agent platform for financial applications powered by LLMs. |
| [FinMem](https://github.com/pipiku915/FinMem-LLM-StockTrading) | ![Stars](https://img.shields.io/github/stars/pipiku915/FinMem-LLM-StockTrading?style=flat-square) | LLM-based trading agent with layered memory (short/mid/long-term) for evolving market understanding. |
| [QVeris](https://github.com/QVerisAI/qveris-agent-toolkit) | ![Stars](https://img.shields.io/github/stars/QVerisAI/qveris-agent-toolkit?style=flat-square) | Capability routing network for AI agents to discover, inspect, and call 10,000+ real-world financial capabilities through one unified MCP protocol. |

---

## Deep Reinforcement Learning

Frameworks and libraries applying deep reinforcement learning to trading, portfolio management, and market making.

| Project | Stars | Description |
|---------|-------|-------------|
| [FinRL](https://github.com/AI4Finance-Foundation/FinRL) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL?style=flat-square) | The first open-source DRL framework for quantitative finance. Supports PPO, A2C, DDPG, SAC, TD3, and more. |
| [TensorTrade](https://github.com/tensortrade-org/tensortrade) | ![Stars](https://img.shields.io/github/stars/tensortrade-org/tensortrade?style=flat-square) | An RL framework for training, evaluating, and deploying robust trading agents. |
| [ElegantRL](https://github.com/AI4Finance-Foundation/ElegantRL) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/ElegantRL?style=flat-square) | Massively parallel deep reinforcement learning using PyTorch. |
| [FinRL-Trading](https://github.com/AI4Finance-Foundation/FinRL-Trading) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Trading?style=flat-square) | Ensemble strategy using DRL for automated stock trading (ICAIF 2020). |
| [gym-anytrading](https://github.com/AminHP/gym-anytrading) | ![Stars](https://img.shields.io/github/stars/AminHP/gym-anytrading?style=flat-square) | OpenAI Gym trading environment for reinforcement learning. |
| [FinRL-Meta](https://github.com/AI4Finance-Foundation/FinRL-Meta) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Meta?style=flat-square) | Dynamic market environments and standardized datasets for financial RL. |

---

## Machine Learning

General machine learning approaches for financial prediction, alpha generation, and quantitative investment.

| Project | Stars | Description |
|---------|-------|-------------|
| [Qlib](https://github.com/microsoft/qlib) | ![Stars](https://img.shields.io/github/stars/microsoft/qlib?style=flat-square) | Microsoft's AI-oriented quantitative investment platform with full ML pipeline. Supports alpha mining, model training, and backtesting. |
| [ML for Trading](https://github.com/stefan-jansen/machine-learning-for-trading) | ![Stars](https://img.shields.io/github/stars/stefan-jansen/machine-learning-for-trading?style=flat-square) | Code for the book *Machine Learning for Algorithmic Trading*. Comprehensive guide on using ML to add value to trading strategies. |
| [Stock-Prediction-Models](https://github.com/huseinzol05/Stock-Prediction-Models) | ![Stars](https://img.shields.io/github/stars/huseinzol05/Stock-Prediction-Models?style=flat-square) | Collection of ML and deep learning models for stock forecasting, including transformers, LSTMs, and more. |
| [stockpredictionai](https://github.com/borisbanushev/stockpredictionai) | ![Stars](https://img.shields.io/github/stars/borisbanushev/stockpredictionai?style=flat-square) | Complete process for predicting stock price movements using deep learning. |
| [TF Quant Finance](https://github.com/google/tf-quant-finance) | ![Stars](https://img.shields.io/github/stars/google/tf-quant-finance?style=flat-square) | TensorFlow-based library for quantitative finance by Google. Covers options pricing, volatility models, and more. |
| [MLFinLab](https://github.com/hudson-and-thames/mlfinlab) | ![Stars](https://img.shields.io/github/stars/hudson-and-thames/mlfinlab?style=flat-square) | Implementations of methods from *Advances in Financial Machine Learning* by Marcos Lopez De Prado. |
| [Adv_Fin_ML_Exercises](https://github.com/BlackArbsCEO/Adv_Fin_ML_Exercises) | ![Stars](https://img.shields.io/github/stars/BlackArbsCEO/Adv_Fin_ML_Exercises?style=flat-square) | Experimental solutions to exercises from *Advances in Financial Machine Learning*. |
| [AlphaPy](https://github.com/ScottfreeLLC/AlphaPy) | ![Stars](https://img.shields.io/github/stars/ScottfreeLLC/AlphaPy?style=flat-square) | ML framework for both speculators and data scientists. Automated feature engineering and model selection. |
| [fin-ml](https://github.com/tatsath/fin-ml) | ![Stars](https://img.shields.io/github/stars/tatsath/fin-ml?style=flat-square) | Code for case studies in *Machine Learning and Data Science Blueprints for Finance*. |

---

## Quantitative Trading & Backtesting

Frameworks for algorithmic trading, strategy backtesting, and automated trading bots.

| Project | Stars | Description |
|---------|-------|-------------|
| [FreqTrade](https://github.com/freqtrade/freqtrade) | ![Stars](https://img.shields.io/github/stars/freqtrade/freqtrade?style=flat-square) | Free, open-source crypto trading bot. Supports backtesting, strategy optimization, and live trading on many exchanges. |
| [Backtrader](https://github.com/backtrader/backtrader) | ![Stars](https://img.shields.io/github/stars/backtrader/backtrader?style=flat-square) | Feature-rich Python framework for backtesting and live trading. Supports multiple data feeds and brokers. |
| [QuantConnect/Lean](https://github.com/QuantConnect/Lean) | ![Stars](https://img.shields.io/github/stars/QuantConnect/Lean?style=flat-square) | Algorithmic trading engine built for strategy research, backtesting, and live trading. Multi-asset support. |
| [Hummingbot](https://github.com/hummingbot/hummingbot) | ![Stars](https://img.shields.io/github/stars/hummingbot/hummingbot?style=flat-square) | Open-source crypto market making and arbitrage bot. Gateway to CeFi and DeFi exchanges. |
| [Jesse](https://github.com/jesse-ai/jesse) | ![Stars](https://img.shields.io/github/stars/jesse-ai/jesse?style=flat-square) | Advanced algo-trading framework for crypto. Strategy development, backtesting, and live trading. |
| [VectorBT](https://github.com/polakowo/vectorbt) | ![Stars](https://img.shields.io/github/stars/polakowo/vectorbt?style=flat-square) | Blazing fast vectorized backtesting and trading analysis using NumPy and Pandas. |
| [HFT-LOB-Trading-ML](https://github.com/rorysroes/SGX-Full-OrderBook-Tick-Data-Trading-Strategy) | ![Stars](https://img.shields.io/github/stars/rorysroes/SGX-Full-OrderBook-Tick-Data-Trading-Strategy?style=flat-square) | High-frequency trading strategies using ML on full order book tick data. |

---

## Data Sources

Tools and APIs for accessing financial market data — stocks, crypto, forex, and alternative data.

| Project | Stars | Description |
|---------|-------|-------------|
| [OpenBB Terminal](https://github.com/OpenBB-finance/OpenBBTerminal) | ![Stars](https://img.shields.io/github/stars/OpenBB-finance/OpenBBTerminal?style=flat-square) | Open-source investment research platform. Access stock, crypto, forex, and macro data with built-in analysis tools. |
| [CCXT](https://github.com/ccxt/ccxt) | ![Stars](https://img.shields.io/github/stars/ccxt/ccxt?style=flat-square) | Unified JavaScript/Python/PHP library for 100+ cryptocurrency exchange APIs. Trading and market data. |
| [yfinance](https://github.com/ranaroussi/yfinance) | ![Stars](https://img.shields.io/github/stars/ranaroussi/yfinance?style=flat-square) | Download market data from Yahoo Finance. Stocks, ETFs, mutual funds, options, and more. |
| [TuShare](https://github.com/waditu/tushare) | ![Stars](https://img.shields.io/github/stars/waditu/tushare?style=flat-square) | Financial data interface for Chinese stock markets. Historical and real-time data. |
| [StockSharp](https://github.com/StockSharp/StockSharp) | ![Stars](https://img.shields.io/github/stars/StockSharp/StockSharp?style=flat-square) | Algorithmic trading and quantitative analysis platform. Connects to multiple brokers and exchanges. |
| [FinRL-Meta](https://github.com/AI4Finance-Foundation/FinRL-Meta) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Meta?style=flat-square) | Dynamic datasets and market environments for stock, crypto, and forex. |
| [FinanceDatabase](https://github.com/JerBouma/FinanceDatabase) | ![Stars](https://img.shields.io/github/stars/JerBouma/FinanceDatabase?style=flat-square) | Comprehensive database of 300,000+ symbols: Equities, ETFs, Funds, Indices, Currencies, and Crypto. |
| [Binance](https://github.com/binance/binance-connector-python) | ![Stars](https://img.shields.io/github/stars/binance/binance-connector-python?style=flat-square) | Official Python connector for Binance APIs. Spot, futures, and market data. |
| [Alpaca](https://github.com/alpacahq/alpaca-py) | ![Stars](https://img.shields.io/github/stars/alpacahq/alpaca-py?style=flat-square) | Official Python SDK for Alpaca. Commission-free stock trading API with paper/live trading. |
| [WRDS](https://github.com/wharton/wrds) | ![Stars](https://img.shields.io/github/stars/wharton/wrds?style=flat-square) | Python interface to Wharton Research Data Services for academic financial research. |

---

## Technical Analysis

Libraries for computing technical indicators and performing quantitative analysis on market data.

| Project | Stars | Description |
|---------|-------|-------------|
| [TA-Lib](https://github.com/mrjbq7/ta-lib) | ![Stars](https://img.shields.io/github/stars/mrjbq7/ta-lib?style=flat-square) | Python wrapper for TA-Lib. 200+ technical analysis functions: candlestick patterns, momentum, volatility, and more. |
| [ta](https://github.com/bukosabino/ta) | ![Stars](https://img.shields.io/github/stars/bukosabino/ta?style=flat-square) | Technical analysis library using Pandas and NumPy. Includes 40+ indicators out of the box. |
| [Clairvoyant](https://github.com/anfederico/Clairvoyant) | ![Stars](https://img.shields.io/github/stars/anfederico/Clairvoyant?style=flat-square) | Identify and monitor social/historical cues for short-term stock movement. |

---

## Portfolio Management & Risk

Tools for portfolio optimization, risk analysis, and asset allocation.

| Project | Stars | Description |
|---------|-------|-------------|
| [PyPortfolioOpt](https://github.com/robertmartin8/PyPortfolioOpt) | ![Stars](https://img.shields.io/github/stars/robertmartin8/PyPortfolioOpt?style=flat-square) | Portfolio optimization in Python. Classical efficient frontier, Black-Litterman, Hierarchical Risk Parity, and more. |
| [Riskfolio-Lib](https://github.com/dcajasn/Riskfolio-Lib) | ![Stars](https://img.shields.io/github/stars/dcajasn/Riskfolio-Lib?style=flat-square) | Portfolio optimization and quantitative strategic asset allocation. Supports 20+ risk measures. |
| [OLPS](https://github.com/OLPS/OLPS) | ![Stars](https://img.shields.io/github/stars/OLPS/OLPS?style=flat-square) | Toolbox for On-Line Portfolio Selection strategies. |

---

## Sentiment Analysis & NLP

Tools for extracting trading signals from text — news, social media, SEC filings, and earnings calls.

| Project | Stars | Description |
|---------|-------|-------------|
| [FinBERT](https://github.com/ProsusAI/finBERT) | ![Stars](https://img.shields.io/github/stars/ProsusAI/finBERT?style=flat-square) | Pre-trained NLP model for financial sentiment analysis. Fine-tuned on financial communication text. |
| [VADER](https://github.com/cjhutto/vaderSentiment) | ![Stars](https://img.shields.io/github/stars/cjhutto/vaderSentiment?style=flat-square) | Valence Aware Dictionary and sEntiment Reasoner. Rule-based sentiment analysis tool, widely used for financial social media and news text. |
| [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinGPT?style=flat-square) | Financial LLMs with built-in sentiment analysis capabilities via fine-tuning. |

---

## Trading Platforms

End-to-end platforms for algorithmic trading with broker integration.

| Project | Stars | Description |
|---------|-------|-------------|
| [FinRL-X](https://github.com/AI4Finance-Foundation/FinRL-Trading) | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Trading?style=flat-square) | AI-native modular infrastructure for quantitative trading. Unifies data processing, strategy construction, backtesting, and broker execution with RL/LLM support. [Paper](https://arxiv.org/abs/2603.21330) |
| [QuantConnect/Lean](https://github.com/QuantConnect/Lean) | ![Stars](https://img.shields.io/github/stars/QuantConnect/Lean?style=flat-square) | Algorithmic trading engine. Multi-asset support with cloud integration for backtesting and live trading. |
| [StockSharp](https://github.com/StockSharp/StockSharp) | ![Stars](https://img.shields.io/github/stars/StockSharp/StockSharp?style=flat-square) | Algorithmic trading for stocks, forex, crypto, and options. GUI and API-based development. |

---

## Visualization & Rendering

Tools for visualizing market data, trading activity, and agent performance.

| Project | Stars | Description |
|---------|-------|-------------|
| [mplfinance](https://github.com/matplotlib/mplfinance) | ![Stars](https://img.shields.io/github/stars/matplotlib/mplfinance?style=flat-square) | Financial data visualization using Matplotlib. Candlestick charts, OHLC, Renko, and more. |
| [TradingGym](https://github.com/Yvictor/TradingGym) | ![Stars](https://img.shields.io/github/stars/Yvictor/TradingGym?style=flat-square) | Toolkit for training and backtesting RL algorithms with real-time rendering. |

---

## High Performance Computing

| Project | Stars | Description |
|---------|-------|-------------|
| [NumPy](https://github.com/numpy/numpy) | ![Stars](https://img.shields.io/github/stars/numpy/numpy?style=flat-square) | The fundamental package for scientific computing with Python. Foundation for most quantitative finance libraries. |
| [Azure HPC](https://azure.microsoft.com/en-us/solutions/high-performance-computing/financial-services/) | - | Azure high-performance computing for financial services — risk simulation, pricing, and analytics. |

---

## Research Papers & Surveys

Key academic papers on AI in finance.

### Surveys

- Hambly, Ben, Renyuan Xu, and Huining Yang. "[Recent Advances in Reinforcement Learning in Finance](https://arxiv.org/abs/2112.04553)." *arXiv preprint arXiv:2112.04553*, 2021.
- "[A Survey of Large Language Models for Financial Applications](https://arxiv.org/abs/2402.02315)." *arXiv*, 2024. Covers FinGPT, BloombergGPT, and domain-specific fine-tuning.
- "[FinAgent: A Multimodal Foundation Agent for Financial Trading](https://arxiv.org/abs/2402.18485)." *arXiv*, 2024. Multimodal agent processing text, tables, and charts.
- "[FinRobot: An Open-Source AI Agent Platform for Financial Applications](https://arxiv.org/abs/2405.14767)." *arXiv*, 2024.
- "[Data-Centric FinGPT: Open-Source Financial Large Language Models](https://arxiv.org/abs/2307.10485)." *arXiv*, 2023. Data-centric approach to building financial LLMs.

### Selected Papers

- "[Deep Reinforcement Learning for Automated Stock Trading: An Ensemble Strategy](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3690996)." *ICAIF 2020*. The ensemble strategy behind FinRL-Trading.
- "[FinRL: Deep Reinforcement Learning Framework to Automate Trading in Quantitative Finance](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3955949)." *ICAIF 2021*.
- "[FinRL-Meta: Market Environments and Benchmarks for Data-Driven Financial Reinforcement Learning](https://arxiv.org/abs/2211.03107)." *NeurIPS 2022*.
- "[FinMem: A Performance-Enhanced LLM Trading Agent with Layered Memory](https://arxiv.org/abs/2311.13743)." *arXiv*, 2023. Novel memory architecture for LLM trading agents.
- "[TradingAgents: Multi-Agents LLM Financial Trading Framework](https://arxiv.org/abs/2412.20138)." *arXiv*, 2024.

---

## Books

- Giller, Graham L. *Adventures in Financial Data Science*. Giller Investments, 2020.
- Jansen, Stefan. *Machine Learning for Algorithmic Trading*. 2nd ed. Packt, 2020. [Code](https://github.com/stefan-jansen/machine-learning-for-trading)
- De Prado, Marcos Lopez. *Advances in Financial Machine Learning*. Wiley, 2018.
- Tatsat, Hariom, Sahil Puri, and Brad Lookabaugh. *Machine Learning and Data Science Blueprints for Finance*. O'Reilly, 2020. [Code](https://github.com/tatsath/fin-ml)
- Dixon, Matthew F., Igor Halperin, and Paul Bilokon. *Machine Learning in Finance: From Theory to Practice*. Springer, 2020.

---

## Contributing

Contributions are welcome! If you have suggestions for new projects or improvements:

1. Fork this repository.
2. Add your project in the appropriate section, following the existing format.
3. Submit a pull request with a brief description of the addition.

**Selection criteria**: Projects should be actively maintained, well-documented, and provide genuine value to the AI for finance community. We particularly welcome:
- Open-source tools with demonstrated community adoption
- Research projects with accompanying papers
- Frameworks that solve real problems in quantitative finance

---

## License

This project is licensed under the [MIT License](LICENSE).

---

**Feedback**: If you have any ideas or want content added to this list, feel free to [open an issue](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance/issues) or [submit a PR](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance/pulls).
