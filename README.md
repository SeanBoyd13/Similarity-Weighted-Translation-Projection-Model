# Similarity Weighted Translation Projection Model
Producing projections for personalized translation factors to NHL based on similar historical player profiles. Coined "S.W.A.T." (Similarity-Weighted Approximate Translation).

## Project Details
This project is a framework constructed to retrieve historical data from drafted prospects using nhl.com and records.nhl.com APIs, which is used to compute similarity for past players of the same position playing in the same league. This similarity metric is then used to weight the translation factors of past players as they transitioned to various leagues. Through a complex path-weighting algorithm a predicted translation factor, for which a players points-per-game will be adjusted by as they transition to the NHL in the succeeding season, is computed. Through testing thus far, this produced projection has outperformed the most advanced "NHLe" (NHL Equivalency) models, which employ constant translation factors for all players transitioning from a specific league to the NHL, at predicting the point totals and point paces of rookies entering the NHL.

## Contents
- **Code (Colab):** Python notebook containing framework used to produce personalized translation factors.
- **Data (CSV):** Comparison between leading projection models for NHL point production in rookie season.
