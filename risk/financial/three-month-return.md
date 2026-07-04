---
type: Financial Metric
title: Three-Month Return
description: How the 3-month Treasury yield serves as the risk-free rate in risk-adjusted models
tags: [financial, returns, risk-free-rate, benchmark]
timestamp: 2025-06-15T00:00:00Z
---

# Three-Month Return: Investment Risk

When analyzing investing risk, the "three-month return" is almost exclusively used as a benchmark proxy rather than as a standalone metric for a stock's risk.

Specifically, it is used as the risk-free rate in risk-adjusted performance models.

## Questions This Answers

- What return could I earn with virtually zero risk, and is this stock beating that baseline?
- Is this stock generating enough excess return to justify the risk I'm taking?
- How do I calculate whether my portfolio manager is adding real value after accounting for risk-free alternatives?
- What baseline should I use when modeling expected returns for a risky asset?

## The Three-Month U.S. Treasury Bill (T-Bill)

In financial modeling, analysts need a baseline measure of return that an investor could achieve with virtually zero risk of financial loss. The 3-month U.S. Treasury bill yield is the industry standard proxy for this "risk-free rate".

## Key Risk Metrics Using the 3-Month Return

The 3-month return serves as the foundational risk-free rate variable in these critical risk analysis formulas:

- **Sharpe Ratio:** This metric measures how much excess return you are receiving for the extra volatility you endure for holding a riskier asset like a stock. The formula is:

  $$\text{Sharpe Ratio} = \frac{R_{\text{stock}} - R_{\text{3-month Treasury}}}{\sigma}$$

- **Capital Asset Pricing Model (CAPM):** This model calculates the expected rate of return for a stock based on its risk relative to the broader market. The 3-month return acts as the starting point to which a risk premium is added:

  $$\text{Expected Return} = R_f + \beta \times (R_m - R_f)$$

- **Jensen's Alpha:** Alpha measures the risk-adjusted performance of a stock relative to a benchmark index. The calculation strips out the 3-month risk-free return to identify the actual value added by the portfolio manager or the stock's specific performance.

## Alternative Uses of "Three Months"

While the return of a 3-month T-Bill is used to measure baseline risk, looking at the 3-month return of the stock itself is generally used for:

- **Short-Term Momentum Analysis:** Gauging immediate, short-term bullish or bearish trends.
- **Volatility and Value-at-Risk (VaR) Calibration:** Setting near-term limits on how much a portfolio is allowed to drop during a quarter.

## Key Risks and Limitations

- **Not a Direct Stock Risk Metric:** The 3-month T-Bill yield measures macro interest rate conditions, not the risk of any individual stock. Changes in this rate affect all equities simultaneously.
  - *How to address:* Use the 3-month return strictly as a benchmark input for risk-adjusted models (Sharpe, CAPM), not as a standalone indicator of stock quality. The value of this metric is in what it tells you about relative attractiveness of equities vs. cash — not about any specific company.
- **Assumption of "Risk-Free":** While U.S. Treasuries are considered virtually risk-free, inflation can erode real returns, and extreme scenarios (debt ceiling crises) introduce brief uncertainty.
  - *How to address:* During periods of elevated inflation, compare the nominal T-Bill yield to the current inflation rate. If inflation exceeds the T-Bill yield, the "risk-free" return is actually negative in real terms — meaning the true hurdle for equities to clear is higher than the nominal yield suggests.
- **Model Sensitivity:** Small changes in the risk-free rate propagate through CAPM, Sharpe, and DCF models, potentially shifting valuations and risk assessments for entire portfolios.
  - *How to address:* Run sensitivity analysis on your models by varying the risk-free rate ±0.5%. If your investment thesis changes materially with a small rate shift, the conclusion is fragile and should be supported by additional valuation methods (comparables, fundamental screens) rather than relying solely on rate-sensitive models.
- **Lag in Reflecting Conditions:** The 3-month yield responds to Fed policy and market expectations with a lag, meaning models using it may temporarily misrepresent the current opportunity cost of equity investing.
  - *How to address:* During periods of active Fed rate changes, check market-implied forward rates (Fed funds futures) alongside the current 3-month yield to anticipate where the risk-free rate is heading. Adjust your required equity risk premium if rates are expected to change significantly in the near term.

## Further Research

For a practical understanding of how the risk-free rate feeds into portfolio models, review the [Investopedia Risk-Free Rate Guide](https://www.investopedia.com/terms/r/risk-freerate.asp) or the [Investopedia CAPM Guide](https://www.investopedia.com/terms/c/capm.asp). To track current 3-month Treasury yields, see the [U.S. Treasury Daily Yield Curve Rates](https://home.treasury.gov/resource-center/data-chart-center/interest-rates/TextView?type=daily_treasury_yield_curve).
