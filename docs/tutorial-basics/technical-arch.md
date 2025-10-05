---
sidebar_position: 2
---

# Technical Architecture

# 2.1 System Overview

Cardexscan operates as a DEX aggregator on the Cardano blockchain, utilizing a sophisticated routing algorithm to optimize trade execution. The platform integrates with various DEXs to aggregate liquidity and provide users with the best available rates.

# 2.2 Key Components

- **Aggregator/Routing Engine**: The core of Cardexscan’s functionality, responsible for routing trades through the most efficient paths across multiple DEXs. The engine dynamically evaluates trading routes to minimize slippage and ensure optimal execution.

- **Real-Time Data Feeds**: Integration with real-time data sources allows Cardexscan to provide up-to-date market information, including price changes, trading volumes, and liquidity availability.

- **User Interface**: An intuitive interface that displays real-time charts, trading options, and analytics, enabling users to make informed trading decisions with ease.

- **Security Protocols**: Robust security measures are implemented to protect user data and ensure safe transactions. This includes smart contract auditing and secure key management practices.

# 2.3 Routing Algorithm

The routing algorithm is designed to optimize trade execution by:

- **Evaluating Multiple Paths**: The algorithm assesses various trading routes across integrated DEXs to find the most efficient path with minimal slippage.

- **Dynamic Liquidity Aggregation**: By sourcing liquidity from multiple exchanges, the algorithm ensures deeper liquidity pools and better trade rates.

- **Price Impact Analysis**: The algorithm considers potential price impacts and adjusts routes accordingly to minimize slippage and improve trade outcomes.

- **Optimal Routing Path**: To determine the optimal routing path, the algorithm needs to evaluate multiple possible paths and choose the one with the lowest total cost or slippage. This can be expressed as:

Optimal route path
We will publish a detailed medium article on our Dex Aggregator Routing Engine. Stay tuned.

