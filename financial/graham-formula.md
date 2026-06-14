# Graham Formula: Investment Risk

The Graham Formula is used in investing primarily to screen for undervalued stocks and to establish a margin of safety. By quantifying a stock's "intrinsic value," it tells you the absolute maximum price a conservative investor should pay, mitigating the risk of overpaying and subsequent capital loss.

## Questions This Answers

- What is the maximum price I should pay for this stock as a conservative investor?
- Does the current stock price provide a meaningful margin of safety against loss?
- Is the market pricing this stock far above what its earnings and assets justify?
- Am I investing during a bubble where prices have disconnected from fundamentals?

## Applications in Risk Analysis

### Classic Valuation Formula (Intrinsic Value)

This formula calculates a company's fair value using earnings, growth, and prevailing interest rates:

$$\text{Intrinsic Value} = \frac{EPS \times (8.5 + 2g) \times 4.4}{Y}$$

- **EPS:** Trailing twelve months Earnings Per Share.
- **8.5:** The base P/E ratio Graham assigned to a zero-growth company.
- **g:** Expected long-term earnings growth rate (typically 7–10 years).
- **4.4:** The average yield of high-grade corporate bonds when the formula was created.
- **Y:** The current yield on high-grade corporate bonds, used to compare stock returns against safe, risk-free assets.

- **Where it's used:** Screening stocks by comparing the calculated intrinsic value to the current market price across an entire watchlist or universe of equities.
- **Risk context:** If the calculated intrinsic value is significantly higher than the current market price, the stock provides a margin of safety. If the market price is much higher than the intrinsic value, it flags the stock as high risk for capital loss.

### Graham Number (Maximum Price Ceiling)

This is a simplified, shortcut version of Graham's principles used as a general test for attractive pricing:

$$\text{Graham Number} = \sqrt{22.5 \times EPS \times BVPS}$$

- **EPS:** Earnings per share.
- **BVPS:** Book value per share.
- **22.5:** The product of Graham's maximum limits (a P/E of 15 multiplied by a P/B of 1.5).

- **Where it's used:** Identifying the absolute maximum price a defensive investor should pay for a given stock.
- **Risk context:** It ensures the investor is not paying an inflated premium for earnings or relying heavily on intangible assets, effectively filtering out speculative or high-risk "growth traps."

### Preliminary Stock Screening

Investors utilize both formulas on screeners to quickly filter out expensive, risky stocks.

- **Where it's used:** Building initial candidate lists from broad market universes before deeper fundamental analysis.
- **Risk context:** Rapidly eliminates overvalued names, reducing the chance of anchoring on stocks that carry excessive downside.

### Defensive and Dividend Investing

The formula is ideal for mature companies in stable, asset-heavy industries where future growth is predictable.

- **Where it's used:** Evaluating utilities, industrials, consumer staples, and other sectors with steady earnings and tangible book value.
- **Risk context:** These sectors align well with the formula's assumptions, giving investors higher confidence that the margin of safety is meaningful.

### Sanity Check During Market Bubbles

It grounds an investor in historical, fundamental metrics when market psychology pushes prices too high.

- **Where it's used:** Comparing current valuations against Graham-derived intrinsic values during periods of market euphoria.
- **Risk context:** Helps identify when broad market prices have disconnected from fundamentals, signaling elevated systemic risk.

## Key Risks and Limitations

- **Modern Asset Mismatch:** The formula assumes historical correlations between interest rates, physical assets, and earnings that may not apply to modern, technology-driven companies reliant on intangible assets or exponential growth.
  - *How to address:* Use the Graham Formula primarily for asset-heavy, mature industries (utilities, industrials, banking) where the assumptions hold. For technology and intangible-heavy companies, pair it with DCF modeling or price-to-sales comparisons that better capture non-physical value drivers.
- **Growth Estimate Sensitivity:** Small changes in the assumed growth rate (g) can dramatically swing the intrinsic value calculation, making it unreliable for companies with uncertain futures.
  - *How to address:* Use a conservative growth estimate — ideally the lower of the company's historical [5-year EPS CAGR](../earnings/five-year-cagr.md) and the analyst consensus projection. Run the formula at multiple growth rates (e.g., g = 5%, 7%, 10%) to see how sensitive the result is. If intrinsic value doubles with a small change in g, the output is too unstable to trust.
- **Interest Rate Dependence:** The bond-yield adjustment factor can distort results in extremely low or high interest rate environments compared to the 4.4% baseline.
  - *How to address:* Recognize that when corporate bond yields are well below 4.4%, the formula mechanically produces higher intrinsic values (and vice versa). Adjust your margin of safety requirement accordingly — demand a larger discount to intrinsic value when interest rates are unusually low, since the formula is being more generous in those conditions.

## Contextual Usage

- **Value Investing:** The primary tool for Benjamin Graham-style defensive investors seeking a quantified margin of safety.
- **Screening Tool:** Best used as a first-pass filter rather than a sole decision-making metric.
- **Complementary Metrics:** Best used alongside [price-to-earnings](price-to-earnings.md), [price-to-book](price-to-book.md), [free cash flow](free-cash-flow.md), and [earnings quality](../earnings/earnings-quality.md) to build a complete picture of fundamental risk.

## Further Research

For a detailed walkthrough of the Graham Formula with practical examples, review the [Old School Value Graham Formula Guide](https://www.oldschoolvalue.com/guide-to-stock-valuation/graham-formula/) or the [Investopedia Benjamin Graham's Intelligent Investor Guide](https://www.investopedia.com/articles/07/ben_graham.asp). For understanding how the Graham Number is used alongside modern valuation tools, see the [Investopedia Graham Number Guide](https://www.investopedia.com/terms/g/graham-number.asp).
