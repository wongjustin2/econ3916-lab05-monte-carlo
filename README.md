# Monte Carlo Engine -- Probability & Simulation

## Objective

I used random simulation to test probability ideas and to measure the risk of a \$1M portfolio.

## Methodology

- I simulated 10,000 coin flips and plotted the running share of heads to see the Law of Large Numbers.
- I simulated 10,000 Monty Hall games for the stay and switch strategies and counted the wins.
- I simulated a disease screening test on 100,000 people with prevalence 1%, sensitivity 95% and specificity 90%, and checked the result against Bayes' Theorem.
- I simulated daily returns for a \$1M portfolio and computed Value at Risk and Expected Shortfall from them.
- I estimated pi with random points and checked that Monte Carlo error shrinks like 1/sqrt(n).

## Key Findings

- The running share of heads settled toward the true probability as the flips grew.
- Switching won 6,694 of the 10,000 Monty Hall games.
- 9.2% of positive tests were sick.
- On a \$1M portfolio the 95% VaR was \$19,494 and the 95% ES was \$24,230.
- The Monte Carlo error in the pi estimate shrank like 1/sqrt(n).
