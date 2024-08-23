# Quant Model 1 - Pairs Trading

## Overview

**Quant Model 1 - Pairs Trading** is a quantitative trading strategy that implements pairs trading to exploit relative price movements between correlated assets. This project uses statistical models to identify cointegrated pairs of stocks and generates trading signals based on their price spread.

## Features

- **Pairs Identification**: Detects pairs of assets that exhibit cointegration.
- **Trading Signals**: Generates buy and sell signals based on the spread between paired assets.
- **Backtesting**: Tests the performance of the pairs trading strategy using historical data.
- **Visualization**: Provides visualizations of trading signals, asset spreads, and strategy performance.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/Quant-Model-1---Pairs-Trading.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd Quant-Model-1---Pairs-Trading
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Prepare Data**: Place historical price data for the assets in the `data/` directory.

2. **Run the Pairs Trading Model**

   ```python
   python pairs_trading_model.py
   ```

   This script identifies cointegrated pairs, generates trading signals, and performs backtesting.

3. **View Results**

   ```python
   python visualize_results.py
   ```

   This script provides charts and reports on trading signals, spread analysis, and strategy performance.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
