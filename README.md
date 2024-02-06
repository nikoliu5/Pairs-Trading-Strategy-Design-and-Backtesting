# Pairs-Trading-Strategy-Design-and-Backtesting

This project is focused on the development and backtesting of a Pairs Trading strategy, a market-neutral trading strategy enabling traders to profit from virtually any market conditions: uptrend, downtrend, or sideways movement. The notebook included in this repository walks through the entire process of identifying stock pairs, testing for cointegration, and then designing and backtesting the strategy.


## Data

Our pairs trading strategy selects **Coca-Cola (KO), Pepsi (PEP), and Costco (COST)** based on their alignment within the Consumer Staples sector, particularly under the **XLP index**. This selection is driven by their similar market behaviors and consumer base within this sector, making them ideal for exploiting price relationships. Both KO and PEP are leaders in the beverage industry, while COST is a significant retail entity, ensuring their market actions are closely related due to sectoral similarities.

The RBICS Revenue analysis reveals that KO and PEP are fully concentrated in Food and Beverage Production, whereas COST is dedicated to General Merchandise Retail. However, all three operate under the Consumer Non-Cyclicals sector, indicating a unified market influence despite their niche differences. This sectoral congruence and distinct operational focuses make them suitable for identifying subtle price discrepancies in pairs trading, leveraging their fundamental similarities to maintain a risk-adjusted strategy.

<div align="center">
  <img src="./src_img/KO_RBICS_Rev.png" width="650">
  <p>Figure 1: Coca-Cola RBICS Revenue</p>

  <img src="./src_img/PEP_RBICS_Rev.png" width="650">
  <p>Figure 2: PEPSI RBICS Revenue</p>

  <img src="./src_img/COST_RBICS_Rev.png" width="650">
  <p>Figure 3: COSTCO RBICS Revenue</p>
</div>