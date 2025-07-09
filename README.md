# Spotify-analysis-2018

# Spotify Track Analysis (2018 Top 100)

This project explores the relationship between audio features of the top 100 Spotify tracks from 2018. Using Python and machine learning, it tests hypotheses about how features like loudness, energy, and danceability relate to each other.

##  Dataset
The dataset includes 100 songs and the following features:
- Danceability
- Energy
- Loudness
- Valence
- Tempo
- and more...

##  Hypotheses Explored
1. **Initial Hypothesis**: Loudness predicts danceability.
   - Tested with a Random Forest Classifier.
   - Accuracy: ~65%
   - Conclusion: Weak correlation; not a strong predictor.
   
2. **Revised Hypothesis**: Loudness predicts energy.
   - Tested with Linear Regression.
   - Mean Squared Error: ~1.98
   - Conclusion: Stronger correlation; more appropriate modeling approach.

##  Methods Used
- Pandas & Seaborn for EDA
- Correlation heatmaps, histograms, scatterplots
- Classification (Random Forest)
- Regression (Linear Regression)
- Train/test split (80/20)

##  What I Learned
This project taught me:
- How to explore and clean datasets using Python
- How to form and test hypotheses using visualizations and modeling
- The difference between classification and regression problems
- How to assess model performance and pivot when a hypothesis doesn’t hold

##  Files
-  Full notebook with code and analysis
-  This summary

##  Next Steps
- Try more complex models (e.g. Gradient Boosting)
- Expand dataset (more songs, more years)
- Include Spotify popularity scores if available
