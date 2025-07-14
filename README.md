# Volatility Surface Construction and Arbitrage Analysis

## Project Overview

This project demonstrates the construction and analysis of implied volatility surfaces using real-world market data from S\&P 500 (SPX) options. Leveraging the Yahoo Finance API, it showcases advanced quantitative finance techniques, including the implementation of the Black-Scholes option pricing model, calculation of implied volatility, detailed visualization of the volatility surface, and systematic detection of potential arbitrage opportunities.

This project highlights practical and industry-relevant skills in quantitative analysis and financial modeling, making it particularly suitable for roles such as quantitative analysts, risk analysts, and derivatives traders.

---

## Technologies and Tools

* **Python**

  * `numpy`
  * `pandas`
  * `matplotlib`
  * `scipy`
  * `yfinance`

---

## Key Features

### Real-time Data Retrieval

* Retrieves live options market data for the S\&P 500 via Yahoo Finance.

### Implied Volatility Calculation

* Utilizes Brent's root-finding algorithm for precise volatility estimation derived from market option prices.

### Black-Scholes Model

* Implements the Black-Scholes model to price European-style call options accurately.

### Volatility Surface Visualization

* Offers a comprehensive 3D visualization of the implied volatility surface, illustrating volatility variations across strikes and maturities.

### Arbitrage Detection

* Performs rigorous tests for calendar spread and butterfly spread arbitrage to identify any violations of theoretical financial market constraints.

---

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone <https://github.com/hameed-abiodun/Volatility-Surface-arbitrage>
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

* Open and execute the provided Jupyter notebook (`Volatility-Surface-Arbitrage.ipynb`) step-by-step to replicate the analysis and visualize results.

---

##  Author

* **Hameed Jimoh**
* [GitHub Profile](https://github.com/hameed-abiodun/)
