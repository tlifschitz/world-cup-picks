# Tobi's Picks

**→ [tlifschitz.com/world-cup-picks](https://tlifschitz.com/world-cup-picks/)**

Model-driven FIFA World Cup 2026 predictions for two prediction pools, published automatically — each pick is revealed only **after** its match kicks off, results and pool scores update within the hour.

The model behind it: Elo → Dixon–Coles bivariate Poisson, Shin-devigged betting markets, an explicit model of the opponent field, and a leverage-based picker that maximizes P(top 3) instead of expected points. The full write-up is on the [Theory page](https://tlifschitz.com/world-cup-picks/theory.html).

This repository contains only the built static site. It is updated by GitHub Actions from a private repository holding the model and the full ticket (keeping future picks private is the whole point of a prediction pool).

Fixtures & results from [football-data.org](https://www.football-data.org/).
