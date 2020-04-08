# Discovering winning fantasy basketball strategies with Data Science techniques

This is a self-motivated project to discover successful tactics in fantasy basketball. I love competing against my friends in fantasy basketball, but I never really utilized historic data to formulate strategies for the future. I hope to demonstrate my data science skillset throughout this project.

- Powerpoint presentation summarizing the analysis: [link](https://github.com/jacksonfd8/fantasybasketball_project/blob/master/JAu_Fbball_Insights.pptx)


**For data, I clean and combine multiple data sources before comprehensive analysis:**
- Historical draft results (2015-2018) from Yahoo
- Historical final rosters (2015-2018) from Yahoo
- Basketball Monster Player Rankings from Basketball Monster


### The first phase: Exploratory Data Analysis

**Description of skills exercised:**
- Exploratory data analysis is performed with the use of Python libraries: Pandas and Matplotlib
- Creating a dataset through the use of multiple data sources
- Python skillset is displayed through the use of: written functions, iterations, multiple 'for' loops

- file_name: [fantasybball_proj_eda.ipynb](https://github.com/jacksonfd8/fantasybasketball_project/blob/master/fantasybball_proj_eda.ipynb)

### The second phase: Multi-Class Classification Problem

In fantasy basketball head-to-head leagues, there are 9 categories that two teams compete for. The goal is to win 5 of the 9 categories. I wanted to understand the most prominent categories that high-ranked players had. Furthermore, which categories were not as prominent?

Additionally, there are often 156 players in 12-player leagues. This is where the multi-class classification problem comes in. I wanted to understand if my model could properly predict which bucket a player would end up:
* Top 40 player (Ranked 1-40)
* Top 80 player (Ranked 41-80)
* Top 120 player (Ranked 81-120)
* Top 200 player (Ranked 121-188)

As a fantasy basketball manager, you would hope a majority of your players are in the first two buckets.

**Description of skills exercised:**
- I train and evaluate statistical models through the following algorithms: Logistic Regression and Random Forests
- To prevent an overfitting model, I use train-test split and k-fold cross validation techniques
- I perform feature engineering in hopes of creating a model with improved, predictive accuracy

- file_name: [fantasybball_proj_classification.ipynb](https://github.com/jacksonfd8/fantasybasketball_project/blob/master/fantasybball_proj_classification.ipynb)
