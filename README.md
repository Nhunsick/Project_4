# Bankruptcy Detection in the Taiwanese Stock Market
## Repo Structure
├── Notebooks 
│   └── Data_exploration_and_modeling.ipynb (EDA, cleaning, and modeling)
│   └── Final_notebook.ipynb (recap of work done in first notebook)
├── data
├── images
├── .gitignore
└── README.md
# Overview
In the world of finance there are many different metrics that can determine the financial health of a company, but the clearest and most understandable of these is if a company is facing bankruptcy. Answering the simple question of if a company is on track to go bankrupt in the immediate future can help set off necessary alarm bells in the company that can help management avoid a possible worst case scenario.

We will be using publicly available financial disclosure data to try to predict if a company will go bankrupt in the next fiscal quarter.

# Business Question
How well can we predict if a company is about to go bankrupt by just looking at publicly available financial disclosure data.

# Data Sources
The data used in this projest is originally from the Taiwan Economic Journal collected from 1999 to 2009, it was sourced from Kaggle for this project.

# Results
Of the four models I tested the best was the Random Forest classifier. This resulted in a 94% class 0 recall rate which was the most important statistic for the purposes of this project. It also had a 99.6% class 0 precision rate which means that we were able to be confident that a company would not go bankrupt when the model predicted it wouldn't. 
