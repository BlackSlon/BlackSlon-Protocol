# BlackSlon Energy Indexes: The Decentralized Energy Marketplace Protocol
BlackSlon is a next-generation **protocol** designed to dismantle centralized bottlenecks in European Energy Wholsale markets (power, natural gas, oil products). Inspired by the "Zero Form" of Kazimierz Malewicz and the market revolution of Marc Rich, I strip away inefficient layers of traditional trading.

## The Vision
I have distilled energy valuation of its most exhausting layers: Expiration, Entry/Exit Spread, Credit/Counterparty Risk, Barrier to Entry, Limited Trading Hours and Price Curve/Seasonality. It's a real-time Energy Index generated not by human actions, but by on-chain Liquidty.

## Price Determination Formula
Our protocol utilizes a deterministic bonding curve to ensure transparent price discovery:

$$P = a \cdot e^{b \cdot S}$$

where:
P (Current Price): The real-time price of one Index Participation Token (IPT), representing a fixed unit of energy (100 kWh).
a (Base Market Anchor): This is the "starting point" for the Index price. The protocol uses decentralized oracles to pull the MtM value from physical exchanges/OTC markets/boots on the ground verification
e (Euler's Number): A mathematical constant. In our protocol, it enables continuous growth modeling, ensuring the price curve remains smooth and predictable rather than volatile and gappy.
b (Sensitivity Factor): The Liquidity Multiplier. This parameter dictates how sensitive the price is to buy/sell pressure. For high-volume benchmarks, b is lower; for niche, illiquid markets, b is adjusted to reward early liquidity providers.
S (Supply / Circulating Volume): The total amount of IPTs/energy tokens currently held within the specific index pool. As more participants enter the Liquidty pool, S increases, causing P to move along the curve.

## About the Founder
Energy Commodities Trader with 20+ years of market experience, moving commodities across OTC and Exchange markets of Central, Eastern and Southern Europe (CEE & SEE), but also have been operated on the financial and physical markets of North - Western Europe (NWE), incl. ICE, EEX, EPEX Spot and TGE exchanges. I navigated CEE/SEE illiquidity and NWE liquidity to capture profound market anomalies. I have been trading Natural Gas, Electricity, Crude Oil and Refined Products (Diesel/Gasoline/LPG), as well as Environmental Products, like Carbon Emissions Allowances (EUA), Green Certificates and complex Cross-Commodity Spreads. Alumnus of International Relations (Warsaw University, St. Petersburg State University, MGIMO in Moscow).
