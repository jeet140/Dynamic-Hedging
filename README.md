# Dynamic-Hedging
In financial markets, portfolio hedging is a strategy used to protect an investment portfolio from adverse price movements by taking offsetting positions in related assets. This dynamic multi-asset portfolio hedging strategy integrates options contracts, leveraging Python for automation and real-time data management.

Options contracts are derivatives that give the holder the right, but not the obligation, to buy or sell an underlying asset at a predetermined price. Dynamic hedging adjusts these positions continuously as market conditions change, ensuring that the portfolio remains hedged against fluctuations in the underlying assets.

The strategy primarily uses the Black-Scholes model, a widely-used formula for pricing European options, to hedge exposure to NVDA call options. The Black-Scholes model helps calculate the theoretical price of an option, accounting for factors such as volatility, interest rates, and the asset's current price. By understanding the intuitions behind this model, the hedging strategy addresses potential risks from volatility and underlying movements.

Python scripts are used to automate the execution of hedging strategies, utilizing real-time data from Yahoo Finance to optimize for changes in volatility, rates, and asset movements. Greeks like Delta and Vega are crucial for monitoring how sensitive the portfolio is to changes in these factors, enabling precise adjustments to the hedge.
