# Energy Trading and Risk Management (ETRM) System


[![License](https://img.shields.io/github/license/AntonioPavoni/AI-Commodity-Trading-Assistant-with-CTRM-Integration.svg)](https://github.com/AntonioPavoni/AI-Commodity-Trading-Assistant-with-CTRM-Integration/blob/main/LICENSE)

[![Streamlit Based MVP](https://etrmai-systemv1.streamlit.app/)](https://etrmai-systemv1.streamlit.app/)

A Streamlit-based application for managing energy trading operations, integrating an AI-powered trading assistant, Commodity Trading and Risk Management (CTRM) features, and a market data section with real-time API fetching and charting.

## Overview

The ETRM System is designed to streamline energy trading operations by providing a unified platform that combines trading management, risk analysis, and real-time market data visualization. It leverages AI to assist in making informed trading decisions and offers comprehensive tools for managing both physical and futures trades.

## Features

- **AI-Powered Trading Assistant:** 
  - **Trade Capture:** Capture physical and futures trades with natural language input. Example: "bought 1000 MT corn at 420 FOB Chicago port" or "bought 5 lots corn CBOT at 420 March25".
  - **Trade Information:** Check positions, view trade history, and analyze prices. Example: "what's my corn position?" or "show my recent trades".
  - **Market Data:** Fetch real-time market data such as USDA crop data, historical trends, and market sentiment. Example: "show me corn production in the US" or "what is the current stocks-to-use ratio for soybeans?".

- **Physical Trade Capture and Management:** 
  - Record and manage physical energy trades, ensuring all transactions are accurately documented.
  - Support for trade details including commodity type, trade direction, quantity, price type, and counterparty information.

- **Futures Trade Capture and Management:**
  - Handle futures trading operations efficiently, allowing for seamless integration and management of futures contracts.
  - Track futures trades by commodity, trading type, quantity, price, and counterparty.

- **Position Tracking and Analysis:**
  - Monitor and analyze trading positions to understand exposure and potential risks.
  - Calculate net position by commodity and provide visual analytics for position trends.

- **Risk Analysis and Visualization:**
  - Utilize comprehensive visualizations to understand and mitigate trading risks.
  - Provide various risk metrics and graphical representations to support decision-making.

- **Trade History and Reporting:**
  - Maintain a detailed history of all trades and generate extensive reports.
  - Generate reports such as trade summary, P&L report, and risk report.

- **Market Data Section:**
  - Fetch real-time market data via APIs and visualize it with interactive charts.
  - Include data sources such as USDA crop data, crude oil production, refinery data, and fundamental economic data.

- **Configuration and Customization:**
  - Initial setup and configuration of trading environment, including company information, commodity types, trading types, price sources, and risk management settings.
  - Manage counterparties and set risk limits for different commodities.

## Example Usage

### AI-Powered Trading Assistant

- **Physical Trades:** "bought 1000 MT corn at 420 FOB Chicago port"
- **Futures Trades:** "bought 5 lots corn CBOT at 420 March25"
- **Check Positions:** "what's my corn position?"
- **View Trade History:** "show my recent trades"
- **Analyze Prices:** "what's the current corn price?"

### Market Data Queries

- **USDA Data:** "show me corn production in the US"
- **Historical Trends:** "what is the wheat production trend over the last 5 years?"
- **Market Sentiment:** "what is the current stocks-to-use ratio for soybeans?"
- **Crude Oil Production:** "show me recent crude oil production in Saudi Arabia" (if available)
- **Refinery Data:** "what is the operating capacity in PADD 3?" (if available)
- **Economic Data:** "how is the economy doing?" (if available)

This application is designed to cater to the needs of energy trading professionals by providing a robust and intelligent platform to manage and analyze trading activities
