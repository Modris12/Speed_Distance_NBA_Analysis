# \# NBA Speed \& Distance Analysis



\## Overview:

This Jupyter Notebook analyzes NBA team and player performance using speed and distance metrics. It combines advanced tracking data with win shares, offensive/defensive ratings, and other statistics to uncover relationships between movement and success.

&nbsp;

\## Hypothesis:

There is a non-linear relationship between players total distance covered and average speed during a game and their team’s likelihood of winning.





\- \*\*Team Analysis\*\*

 - Calculates weighted mean speed and distance for each team (offense/defense).

 - Explores correlations between these metrics and win percentage.

 - Visualizes trends with bar plots, scatter plots, LOWESS smoothing, and quadratic fits.

 - Performs ANOVA to test differences across speed/distance bands.

 - Builds regression models to predict win percentage from speed/distance features.

 - Simulates "what-if" scenarios by substituting team metrics.



\- \*\*Player Analysis\*\*

 - Filters players by minutes and games played for robust comparisons.

 - Merges distance/speed data with win shares (WS, OWS, DWS).

 - Computes correlations and multiple correlation coefficients between movement metrics and win shares.

 - Highlights top-20 players by distance and speed, with visualizations.



\- \*\*Advanced Modeling\*\*

 - Uses cubic splines and LOESS for nonlinear relationships.

 - Calculates Variance Inflation Factor (VIF) to check multicollinearity.

 - Multiple regression and correlation analyses for combined predictors.



\## How to Use



1\. \*\*Data Requirements\*\*: The notebook assumes access to NBA tracking data (speed, distance, win shares, etc.) in pandas DataFrames.

2\. \*\*Dependencies\*\*: Requires `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, and `scipy`.

3\. \*\*Execution\*\*: Run cells sequentially. Visualizations and statistical outputs will be generated for each analysis step.



\## Key Insights



\- Both offensive and defensive movement metrics contribute to team success.

\- Regression and correlation analyses quantify the impact of speed/distance on performance.

\- The hypothesis is supported, based on the findings.



\## Visualizations



\- Bar charts for top teams/players by speed and distance.

\- Scatter plots with regression and smoothing lines.

\- Heatmaps for correlation matrices.

\- Annotated plots for top performers.



\## Customization



\- Adjust filtering criteria for players (minutes, games played).

\- Modify regression features or add new metrics.

\- Extend analyses to include additional seasons or custom metrics.
