# Statistical Analysis: Predicting Song Popularity

Linear regression course project, Ben-Gurion University, 2025. Team project.

**Goal:** build a reliable, interpretable multiple linear regression model that predicts a song's popularity from its audio features (energy, danceability, acousticness, tempo, valence and more).

## What we did
- **Feature engineering:** converted tempo and song length into categories (slow / medium / fast) with dummy variables, and added interaction terms such as energy × danceability.
- **Variable selection:** backward and forward stepwise selection.
- **Diagnostics:** tested the classical regression assumptions and found non-constant error variance and non-normal residuals.
- **Model improvement:** Box-Cox analysis of the response (λ close to 1, so the original scale was kept), second- and third-order polynomial terms for energy, and a log transformation for instrumentalness.
- **Final model:** the lowest AIC in the process (168,538.3), with only significant variables.

## Report
[Full report](report/Song_Popularity_Regression_Report.pdf) (Hebrew)
