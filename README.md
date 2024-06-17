# Pok-mon-Data-Analysis-and-Classification-
#Introduction
This repository contains an analysis of Pokémon data using Python libraries such as Pandas, Seaborn, Matplotlib, and Scikit-learn. The dataset used (pokemon.csv) includes various attributes of Pokémon such as base stats, types, generation, and more.

#Analysis Overview
The analysis covers several aspects of the Pokémon dataset, aiming to uncover patterns, correlations, and differences across different Pokémon types, generations, and legendary status.

#Data Cleaning and Preprocessing
The initial steps involved:

Loading the dataset using Pandas.
Handling missing values by filling them with appropriate defaults (e.g., mean for numeric values, 'NIL' for categorical).
#Exploratory Data Analysis (EDA)
Distribution and Correlation of Base Stats:

Visualized using histograms, scatter plots, pair plots, and correlation matrices.
#Insights:
Base stats like HP, Attack, Defense, etc., vary across Pokémon types and generations.
Strong correlations exist between certain stats, e.g., HP vs. Defense.
Statistical Tests:

Conducted ANOVA to test differences in base stats between Pokémon generations.
T-test to compare base happiness between legendary and non-legendary Pokémon.
Results highlighted significant differences in stats and happiness levels across groups.
#Visualization:

Used various plots (box plots, scatter plots, bar plots, histograms) to visualize:
Distribution of stats across Pokémon types.
Relationships between stats like HP vs. Defense, Speed vs. Attack.
Average stats and base happiness by type and generation.
#Machine Learning Model (XGBoost):

Built an XGBoost classifier to predict whether a Pokémon is legendary based on its stats and other attributes.
Evaluated model performance using metrics like accuracy, precision, recall, and F1-score.
Key Findings
Different Pokémon types exhibit variations in stats (e.g., Attack, Defense) and base happiness.
Legendary Pokémon generally have higher base stats compared to non-legendary ones.
There are observable trends in stats across Pokémon generations.
Machine learning models can predict legendary status with reasonable accuracy based on base stats and generation.
#Conclusion
This analysis provides valuable insights into the Pokémon universe, showcasing how attributes like types, stats, and generations influence various aspects of Pokémon characteristics. The findings can be useful for enthusiasts, gamers, and researchers interested in understanding Pokémon diversity and characteristics.

For detailed code and visualizations, please refer to the Jupyter Notebook in this repository.
