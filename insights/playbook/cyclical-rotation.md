---
type: Playbook
title: Cyclical Rotation
description: A step-by-step process for identifying the business cycle phase and positioning in sectors most likely to outperform
tags: [playbook, cyclical, macro, sectors, rotation]
generated: { by: human:kengibson1111, at: 2025-06-15T00:00:00Z }
---

# Cyclical Rotation

The economy moves in cycles. Sectors that thrive in expansion get crushed in contraction, and vice versa. This playbook provides a structured process for reading the cycle, determining its direction, and positioning in the sectors and companies most likely to benefit from what comes next.

The core insight: **the stock market leads the economy by 6–9 months.** By the time a recession is officially declared, the best recovery stocks have often already bottomed. By the time expansion feels obvious to everyone, the best cyclical stocks have already run. Your job is to read the signals early enough to position ahead of consensus.

This playbook works in three steps:

1. **Read the cycle** — Where are we, and which direction are we headed?
2. **Map to sectors** — Which sectors should I favor or avoid given the phase and direction?
3. **Screen for quality** — Within the favored sectors, which companies have the strongest fundamentals?

---

## Step 1: Read the Economic Cycle

You need to determine two things: what phase you're *in* and which direction you're *headed*. The second matters more than the first for investment positioning.

### Leading Indicators (Signal Direction Change)

These move *before* the economy turns. They tell you where things are headed, not where they are today.

| Indicator | What It Signals | Where to Find It |
|-----------|----------------|-----------------|
| **Yield Curve (10Y − 2Y Treasury Spread)** | Inversion (negative spread) has preceded every U.S. recession since 1970. Steepening after inversion (spread moving back toward positive) signals recovery is approaching. | [FRED: T10Y2Y](https://fred.stlouisfed.org/series/T10Y2Y) |

**How the yield curve works mechanically:** The 2-year Treasury yield closely tracks where the market expects the Fed funds rate to be over the next 1–2 years. The 10-year yield reflects much longer-horizon expectations about growth, inflation, and policy over a decade — it's more "free market" in the sense that the Fed has less direct influence over it. The spread (10Y − 2Y) therefore measures the gap between "what the bond market expects the economy to look like long-term" and "what the Fed is doing in the near term." When the spread goes negative, the bond market is saying: "The Fed is keeping short rates high now, but economic conditions will force rates lower eventually" — a forecast of weakness.

**How inversion leads to recession (typical mechanism):** Inversion compresses bank net interest margins (banks borrow short and lend long), which tightens credit availability → businesses slow hiring and investment → unemployment rises → recession arrives 12–24 months after the initial inversion → the Fed responds by cutting short rates → the curve re-steepens (moves positive) → that re-steepening is the actionable signal that recovery is approaching.

**Important limitation (2022–2024 example):** The 10Y-2Y spread inverted around July 2022 and remained negative into late 2024 — one of the longest inversions on record. Yet no official recession followed. Aggressive fiscal spending (CHIPS Act, IRA, infrastructure), strong consumer balance sheets from pandemic-era savings, and AI-driven capital investment collectively prevented the credit contraction that normally follows inversion. This demonstrates that inversion is a necessary-but-not-sufficient condition for recession. Confirmation from other indicators (rising jobless claims, declining PMI, falling LEI) remains essential before acting on the inversion signal alone.

| **ISM Manufacturing PMI** | Below 50 = contraction. Above 50 = expansion. The direction of change matters more than the level. A PMI rising from 45 to 48 is bullish even though it's still below 50. | [ISM Report on Business](https://www.ismworld.org/supply-management-news-and-reports/reports/ism-report-on-business/) |
| **Initial Jobless Claims (4-week avg)** | Rising claims signal weakening labor market. Falling claims signal strengthening. This turns before the unemployment rate does. | [FRED: ICSA](https://fred.stlouisfed.org/series/ICSA) |
| **Conference Board Leading Economic Index (LEI)** | Composite of 10 leading indicators. Six consecutive monthly declines historically signal recession within 6–12 months. | [Conference Board LEI](https://www.conference-board.org/topics/us-leading-indicators) |
| **Building Permits** | A leading indicator of construction activity, consumer confidence, and interest rate sensitivity. Sharp declines precede economic weakening. | [FRED: PERMIT](https://fred.stlouisfed.org/series/PERMIT) |
| **Consumer Confidence / Expectations** | The expectations component (not the present situation) leads spending decisions. A sharp drop in expectations precedes reduced discretionary spending. | [Conference Board Consumer Confidence](https://www.conference-board.org/topics/consumer-confidence) |
| **Credit Spreads (High Yield OAS)** | The gap between corporate bond yields and Treasury yields of similar maturity. Narrowing spreads signal investor optimism and easy credit (risk-on). Widening spreads signal rising default fears and credit tightening (risk-off). Spreads typically widen 3–6 months before recessions become obvious. | [FRED: BAMLH0A0HYM2](https://fred.stlouisfed.org/series/BAMLH0A0HYM2) |

**How credit spreads complement the yield curve:** The yield curve tells you what the bond market thinks about Fed policy and future growth. Credit spreads tell you what the bond market thinks about *default risk and risk appetite*. Together they provide a more complete picture — a flat or inverted yield curve with still-tight credit spreads (as in 2023) suggests the market sees policy risk but not imminent credit stress. An inverted yield curve *plus* rapidly widening credit spreads is a much stronger recession signal because it means both growth expectations and credit conditions are deteriorating simultaneously.

**Boom-time dynamics (AI, dot-com, etc.):** During technology booms, credit spreads often narrow to unusually tight levels because investor optimism is high and companies can issue debt cheaply to fund expansion. This easy credit *fuels* the boom by making growth capital abundant. The risk emerges when the cycle turns — companies that leveraged heavily during the boom face refinancing at much wider spreads, which can turn a slowdown into a credit crisis. Watch for the *rate of change* in spreads rather than the absolute level: a move from 300bps to 500bps in high-yield spreads over 2–3 months is a more urgent signal than a stable 500bps that the market has already adjusted to.

### Coincident Indicators (Confirm Current Phase)

These move with the economy and confirm what phase you're currently in.

| Indicator | What It Confirms | Where to Find It |
|-----------|-----------------|-----------------|
| **Nonfarm Payrolls** | Job growth confirms expansion; job losses confirm contraction. | [BLS Employment Situation](https://www.bls.gov/news.release/empsit.nr0.htm) |
| **Industrial Production** | Directly measures factory, mine, and utility output. Confirms whether manufacturing is expanding or contracting. | [FRED: INDPRO](https://fred.stlouisfed.org/series/INDPRO) |
| **Real Personal Income (ex-transfers)** | Measures organic earning power of consumers — excludes government transfer payments that can mask underlying weakness. | [FRED: W875RX1](https://fred.stlouisfed.org/series/W875RX1) |
| **Real Retail Sales** | Inflation-adjusted consumer spending. Confirms whether consumers are still spending or pulling back. | [FRED: RRSFS](https://fred.stlouisfed.org/series/RRSFS) |

### Federal Reserve Policy (The Amplifier)

Fed actions don't cause the cycle but amplify it. Policy direction tells you how the cycle will evolve.

| Policy Stance | What It Means for Positioning |
|---------------|-------------------------------|
| **Cutting rates aggressively** | Economy is weak or weakening. Defensive sectors now, but begin positioning for recovery plays. Rate-sensitive sectors (real estate, utilities) get near-term relief. |
| **Rates on hold (low)** | Accommodative conditions supporting recovery. Risk assets favored. Growth and cyclicals benefit. |
| **Hiking rates** | Economy is strong but the Fed is tightening. Late-cycle dynamics. Duration-sensitive sectors (high P/E tech, REITs) face headwinds. Energy and materials often peak here. |
| **Rates on hold (high)** | Restrictive conditions constraining growth. Slowdown approaching. Quality and defensives outperform. Debt-heavy companies face refinancing risk. |

### Determining Phase and Direction

Combine the signals above to place yourself on the cycle:

| If You're Seeing... | You're Likely In... | Headed Toward... |
|--------------------|--------------------|--------------------|
| PMI rising, claims falling, yield curve steepening, Fed cutting or on hold low | **Early Expansion** | Continued expansion — favor cyclicals |
| PMI high but plateauing, claims at lows, inflation rising, Fed hiking | **Late Expansion** | Peak and eventual slowdown — begin shifting to quality/defensives |
| PMI falling below 50, claims rising, LEI declining, yield curve inverting or already inverted | **Early Contraction** | Recession — favor defensives, reduce cyclical exposure |
| PMI deeply below 50 but rate of decline slowing, claims peaking, Fed cutting aggressively, extreme pessimism | **Late Contraction** | Recovery approaching — begin positioning in early-cycle cyclicals |

### Key Question

*Is the economy getting better and likely to continue improving, or getting worse and likely to continue deteriorating — and is the market already pricing in the next phase?*

---

## Step 2: Map to Sectors

Once you've identified the current phase and direction, use the [Sector Cycle Map](/insights/reference/sector-cycle-map.md) to determine which sectors to favor and which to avoid.

### Decision Framework

| Cycle Conclusion | Sector Positioning |
|-----------------|-------------------|
| Economy strengthening, likely to continue | Overweight cyclicals: Consumer Discretionary, Industrials, Financials, Technology |
| Economy strong but peaking | Shift toward: Energy, Materials, Healthcare. Reduce: rate-sensitive growth, real estate |
| Economy weakening, recession beginning | Overweight defensives: Consumer Staples, Healthcare, Utilities. Reduce: Discretionary, Financials, Industrials |
| Economy in recession but bottoming | Begin adding early-cycle recovery: Discretionary, Financials, Technology. Hold defensives until confirmation |

### Important Timing Considerations

- **Don't wait for confirmation to act.** By the time GDP prints negative or the NBER officially declares recession, defensive sectors have already outperformed for months. Position on leading indicators, not official announcements.
- **Sector rotation is gradual, not binary.** You don't need to go 100% cyclical or 100% defensive. Shift weightings incrementally as evidence accumulates.
- **The transition phases are where the money is made.** The biggest relative performance happens during the phase *transitions* (late contraction → early expansion, late expansion → early contraction), not during the stable middle of a phase.
- **Relative vs. absolute returns.** In early contraction, even defensive sectors may decline — they just decline less. "Outperformance" during a recession often means losing less, not making money.

### Key Question

*Given the cycle phase and direction, which sectors have the historical wind at their back — and am I early enough to benefit from the rotation?*

---

## Step 3: Screen for Quality Within Favored Sectors

Identifying the right sector is only half the job. Within any sector, quality dispersion is enormous — the best companies outperform the worst by multiples during both expansions and contractions. Use your existing metrics to separate the leaders from the laggards.

### Core Quality Screen

Apply these filters to companies within your favored sectors:

| Filter | What to Check | Why It Matters in Cyclical Positioning |
|--------|---------------|---------------------------------------|
| Earnings stability | [Earnings Stability](/risk/earnings/earnings-stability.md) | Companies with stable earnings through prior cycles are more likely to survive and recover faster |
| Cash flow health | [Operating Cash Flow](/risk/financial/operating-cash-flow.md) | Ensures the company generates real cash, not just paper profits that evaporate in a downturn |
| Margin resilience | [Gross Profit Margin](/risk/financial/gross-profit-margin.md) | High and stable margins indicate pricing power that persists even when demand weakens |
| Balance sheet strength | [Debt-to-Equity](/risk/financial/debt-to-equity.md), [Interest Coverage](/risk/financial/interest-coverage-ratio.md) | Leveraged companies face refinancing risk and bankruptcy in downturns; conservative balance sheets survive |
| Liquidity buffer | [Cash Buffer](/risk/financial/cash-buffer.md), [Current Ratio](/risk/financial/current-ratio.md) | Companies with cash survive demand droughts; those without it get forced into dilutive financing |
| Growth track record | [Revenue Growth](/risk/earnings/revenue-growth.md), [Five-Year CAGR](/risk/earnings/five-year-cagr.md) | Demonstrated growth through prior cycles confirms the business model works across conditions |
| Capital return | [Dividend Growth Rate](/risk/financial/dividend-growth-rate.md) | Companies that maintained or grew dividends through prior downturns signal management confidence and financial resilience |

### Phase-Specific Quality Emphasis

The quality factors that matter most shift with the cycle:

**When positioning for expansion (buying cyclicals):**
- Emphasize operating leverage ([Operating Leverage](/risk/earnings/operating-leverage.md)) — high fixed-cost companies will amplify upside as revenue recovers
- Look for depressed valuations: low [P/E](/risk/financial/price-to-earnings.md) relative to history, compressed [PEG](/risk/financial/peg.md) relative to sector
- Favor companies that maintained investment during the downturn (R&D, capex) — they'll emerge stronger
- Check that the balance sheet survived: no emergency dilution, debt levels manageable

**When positioning for contraction (buying defensives):**
- Emphasize earnings stability and dividend safety — companies that kept paying through 2008–2009 and 2020
- Look for low [debt-to-equity](/risk/financial/debt-to-equity.md) and high [interest coverage](/risk/financial/interest-coverage-ratio.md) — no refinancing risk
- Favor companies with pricing power: [gross profit margin](/risk/financial/gross-profit-margin.md) >40% and stable through prior recessions
- Check [free cash flow](/risk/financial/free-cash-flow.md) coverage of dividends — payout ratio should leave a comfortable buffer

### Apply the P/E Multiple Validation

Once you've identified quality candidates within favored sectors, run them through the [P/E Multiple Validation Playbook](/insights/playbook/pe-multiple-validation.md) to confirm you're not overpaying:

- After a downturn, quality cyclicals should have compressed multiples — verify the compression is overreaction, not justified
- Before a downturn, quality defensives may already carry premium multiples — verify the premium is reasonable given their stability

### Key Question

*Within the favored sector, which specific companies have the financial strength to survive the current phase and the operational quality to outperform in the next one?*

---

## Putting It All Together: Example Scenarios

### Scenario: Late Contraction → Early Expansion Positioning

**Signals:** PMI at 44 but rate of decline slowing. Initial claims peaked 6 weeks ago and trending down. Fed has cut 150bps. Yield curve re-steepening. Consumer confidence expectations ticking up from deep lows.

**Conclusion:** Late contraction, likely approaching recovery within 3–6 months.

**Action:**
1. Consult [Sector Cycle Map](/insights/reference/sector-cycle-map.md) → favor Consumer Discretionary, Financials, Technology
2. Screen within those sectors: look for companies with strong pre-recession earnings track records, manageable debt, intact margins, and deeply compressed valuations
3. Validate multiples: these stocks should look "expensive" on trailing P/E (because trailing earnings are depressed) but attractive on forward P/E and historical P/E range
4. Position incrementally — don't go all-in on a single signal

### Scenario: Late Expansion → Early Contraction Positioning

**Signals:** PMI at 52 but declining for three consecutive months. Initial claims rising from multi-year lows. Yield curve recently inverted. Fed holding rates at 5%+. Inflation still elevated. LEI declining for six months.

**Conclusion:** Late expansion, recession likely within 6–12 months.

**Action:**
1. Consult [Sector Cycle Map](/insights/reference/sector-cycle-map.md) → favor Healthcare, Consumer Staples, Utilities
2. Screen within those sectors: look for companies with 5+ year dividend growth streaks, OCF consistently exceeding net income, gross margins stable through 2020, low leverage
3. Validate multiples: defensives may already carry modest premiums — that's acceptable if earnings stability justifies it, but avoid paying extreme multiples for "safety"
4. Reduce exposure to highly cyclical positions (especially those with high operating leverage and heavy debt)

---

## Common Mistakes

- **Waiting for official confirmation.** The NBER declares recessions 6–12 months after they begin. By then, markets have already priced in the downturn and are pricing recovery. Act on leading indicators.
- **Fighting the Fed.** If the Fed is aggressively cutting, don't stay short cyclicals. If the Fed is aggressively hiking, don't stay long rate-sensitive growth. Policy is the single most powerful force amplifying the cycle.
- **Confusing sector performance with stock selection.** Being in the "right" sector with the "wrong" company (over-leveraged, poor management, weak margins) can still produce losses. Quality screening is non-negotiable.
- **Assuming this cycle is exactly like the last one.** Use the historical patterns as a starting framework, then adjust for current structural differences (inflation regime, AI productivity gains, global trade dynamics, fiscal policy, etc.). See the [AI structural consideration](/insights/reference/sector-cycle-map.md#structural-consideration-ai-and-sector-rotation-2024-2026) in the Sector Cycle Map for how AI specifically affects rotation assumptions.
- **Binary thinking.** The cycle is a continuum, not a light switch. Shift allocations gradually based on weight of evidence rather than making dramatic all-or-nothing moves.
- **Treating cap-weighted sector returns as rotation signals.** Concentration in a few AI-linked mega-caps can make "Technology outperforming" look like a broad sector rotation when it's really a single-theme trade. Use equal-weighted sector data or sub-industry performance as a cross-check.

---

## Metrics and References Used in This Playbook

| Category | Metrics |
|----------|---------|
| Cycle Assessment | ISM PMI, Initial Jobless Claims, Yield Curve, Conference Board LEI, Building Permits, Consumer Confidence, Fed Funds Rate |
| Sector Mapping | [Sector Cycle Map](/insights/reference/sector-cycle-map.md) |
| Quality Screening | [Earnings Stability](/risk/earnings/earnings-stability.md), [Operating Cash Flow](/risk/financial/operating-cash-flow.md), [Gross Profit Margin](/risk/financial/gross-profit-margin.md), [Debt-to-Equity](/risk/financial/debt-to-equity.md), [Interest Coverage](/risk/financial/interest-coverage-ratio.md) |
| Growth & Returns | [Revenue Growth](/risk/earnings/revenue-growth.md), [Five-Year CAGR](/risk/earnings/five-year-cagr.md), [Dividend Growth Rate](/risk/financial/dividend-growth-rate.md), [Operating Leverage](/risk/earnings/operating-leverage.md) |
| Valuation | [P/E](/risk/financial/price-to-earnings.md), [Forward P/E](/risk/financial/price-to-earnings-forward.md), [PEG](/risk/financial/peg.md), [Free Cash Flow](/risk/financial/free-cash-flow.md) |
| Liquidity | [Cash Buffer](/risk/financial/cash-buffer.md), [Current Ratio](/risk/financial/current-ratio.md) |
| Playbook Integration | [P/E Multiple Validation](/insights/playbook/pe-multiple-validation.md) |
