# Football Scouting Across Europe’s Big Five

Interactive, data-driven scouting across the Premier League, LaLiga, Serie A, Bundesliga, and Ligue 1. Search a reference player, set a market-value cap, and compare same-position profiles using twelve per-90 features.

## Explore

- **Interactive dashboard:** [Open the live report](https://juampacasaus.github.io/football-scouting-tfm/)
- **Notebook and analysis:** [Open the Kaggle notebook](https://www.kaggle.com/code/juanpablocasaus/similarity-based-scouting-across-europe-s-big-five)
- **Data:** [Scouting Big Five 2020–2025](https://www.kaggle.com/datasets/juanpablocasaus/scouting-big5-2020-2025)

The 2024/25 season is held out for temporal validation. Across the tested shortlists, 71.2% of similarity-ranked recommendations recorded at least 900 minutes in the Big Five leagues the following season, versus 60.3% for randomly selected cheaper players. A random-forest market-value estimator achieved €4.95M MAE across 807 holdout observations with a published outcome value, compared with €5.45M for an unchanged-value baseline. These results support shortlisting; they are not formal player valuations.

The project combines public FBref, Understat, and Transfermarkt data. Market values are estimates, not transfer fees.

## License

The public Kaggle notebook is published under the Apache License 2.0, as required by Kaggle’s public notebook settings. The English source package and the files in this GitHub repository are licensed under the MIT License.
