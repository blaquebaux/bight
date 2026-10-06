# Blaque Baux Bight

**Volatility-Surface Skew Mean-Reversion — STUB (blocked on data).**

Systematic 25-delta risk-reversal (put skew vs call skew) in SPX / major FX; fade the cheaper side when the differential hits >2.5 sigma extremes.

> **Status: STUB / DATA-BLOCKED.** This sleeve is specified and queued but **not yet built** — it needs an options implied-vol surface — per-strike/per-delta IV for SPX or FX. Alpaca has no options chains (see block for the limits this imposes).

> **Not investment advice.** Educational/research software. See [DISCLAIMER](DISCLAIMER.md) and [LICENSE](LICENSE).

## Honest null (to be tested once the feed exists)

Is extreme skew a persistent negative-carry insurance premium that bleeds out (like shorting tails), rather than a true mean-reverting signal?

## Why it's a stub

The Blaque Baux research stack runs on Alpaca SIP **daily OHLCV + crypto**. Volatility-Surface Skew Mean-Reversion cannot be tested faithfully on
price bars alone — it requires an options implied-vol surface — per-strike/per-delta IV for SPX or FX. Alpaca has no options chains (see block for the limits this imposes). When that feed is wired in, this becomes `bight_1` with the family's standard
fat-tail scorecard (Sharpe / CAGR / maxDD / skew / Jensen's alpha / M-squared), causal signals, and an honest verdict.

## Status

**Stub.** Placeholder for a queued sleeve awaiting a data source beyond price. No code, no backtest, no live capital yet.
