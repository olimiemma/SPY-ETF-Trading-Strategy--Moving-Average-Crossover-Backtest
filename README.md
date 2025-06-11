# SPY ETF Trading Strategy

## Overview

This project implements and evaluates a simple moving-average crossover trading strategy on the SPY ETF (S\&P 500 Exchange-Traded Fund). The strategy uses two technical indicators: the 21-period Exponential Moving Average (EMA) and the 50-period Moving Average (MA).

## Strategy Explanation

* **Buy Signal**: Generated when the 50-period MA crosses above the 21-period EMA (upward crossover).
* **Sell Signal**: Generated when the 21-period EMA crosses below the 50-period MA (downward crossover).

## Implementation

The strategy is coded in Python within a Jupyter notebook environment. The notebook covers:

* Loading historical SPY ETF data.
* Calculating EMA and MA.
* Detecting crossover points to trigger buy/sell signals.
* Recording each trade's entry and exit prices, along with calculated profit or loss (PnL).

## Output

The trading simulation results in a detailed DataFrame including:

* Entry and exit timestamps.
* Entry and exit prices.
* Profit or loss per trade, calculated as:
  $\text{PnL} = \frac{\text{Exit Price}}{\text{Entry Price}} - 1$

## Dependencies

* Python (pandas, numpy, matplotlib)
* Jupyter Notebook for interactive development

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/SPY-Trading-Strategy.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib
```

3. Run the Jupyter notebook:

```bash
jupyter notebook lecture_8.ipynb
```

## Visualization

The notebook includes clear visualizations plotting:

* The SPY price over time.
* The EMA (21 periods) and MA (50 periods) for visual verification of crossover signals.

## Project Structure

```
SPY-Trading-Strategy/
├── lecture_8.ipynb
└── README.md
```

## Contribution

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
