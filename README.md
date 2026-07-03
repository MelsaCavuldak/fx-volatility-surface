# Fx-volatility-surface
Python implementation of an FX Options Pricer (Garman-Kohlhagen) and an advanced 3D Bid/Ask Volatility Surface Builder using market data (ATM, RR, BF).

I developed this repository to demonstrate my skills in quantitative modeling for Foreign Exchange (FX) derivatives using Python. The project is structured around two main components, bridging the gap between fundamental pricing theory and advanced market data interpolation:

I implemented the foundational FX options pricing model (the Black-Scholes equivalent for currencies) from scratch. Through this module, I calculate exact Call/Put prices, derive comprehensive Greeks (Delta, Gamma, Vega, Theta, Rho), and generate detailed sensitivity analyses (e.g., price vs. strike, price vs. maturity) using Jupyter Notebooks.

I engineered an advanced pipeline to reconstruct a complete Bid/Ask volatility surface from standard market quotes (ATM, Risk Reversal, Butterfly). In this section, I perform precise delta-to-strike conversions, interpolate and extrapolate the volatility smile using Cubic Splines (integrating SABR concepts), isolate Bid/Ask liquidity spreads, and render interactive 3D visualizations (Strike × Maturity × Volatility) using Plotly and Matplotlib.
