# fds-project

## Hypothesis
Momentum profits accrue overnight and partially reverse during market hours, and this pattern persists after 2013. We test whether a momentum portfolio (past winners minus past losers) earns higher returns, and higher risk-adjusted returns, when held only overnight (close to next open) than when held only during market hours (open to close). Using WRDS Intraday Indicators midquotes rather than trade prices to remove bid-ask bounce, we then investigate which stock and day characteristics are most strongly associated with the intraday reversal. Candidate characteristics include liquidity (spreads, depth, price impact), the share of the overnight return earned pre-market versus after-hours, retail and institutional order flow, order imbalance, and opening-auction activity.

## Setup

```bash
pip install -r requirements.txt
jupyter notebook HW4_submission.ipynb
```
