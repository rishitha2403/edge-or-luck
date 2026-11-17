Edge or Luck?
An interactive research notebook on one question: is a trading strategy's backtest a real edge, or luck?

Live page: https://rishitha2403.github.io/edge-or-luck/

Experiments
Data snooping: the best of 1,000 zero-edge strategies looks brilliant in-sample and fails out-of-sample.
Transaction costs: how brokerage, STT and slippage shrink a strategy's Sharpe ratio, and the break-even cost per trade.
Law of Large Numbers: how many years of data a Sharpe ratio needs before it means anything (from my undergraduate project).
Walk-forward backtest: momentum and mean reversion on real NIFTY 50 data, tuned on training data, judged on unseen data, with a COVID-crash stress test.
Result on NIFTY 50 (2015–2026, 60% train / 40% test, 10 bps per side)
Momentum, 75-day lookback: training Sharpe 0.94, test Sharpe 0.74, stable across lookbacks from 20 to 150 days.
COVID crash (19 Feb to 23 Mar 2020): strategy −0.6%, NIFTY −36.5%.
Mean reversion: unstable across lookbacks, weaker than buy and hold.
All computation runs in the browser. Load any CSV with Date and Close columns to test other NSE prices.

Built by Ch Rishitha (IIT Kanpur) with AI-assisted coding.

