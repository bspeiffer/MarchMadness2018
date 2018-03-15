# March Madness Bracket Prediction

Worked with a few coworkers to put together a several models and play in the office March Madness Pool.

## Approaches

[`DataPrep_EloFunc_InitialCleanData`](https://github.com/bspeiffer/MarchMadness2018/tree/master/DataPrep_EloFunc_InitialCleanData) - My approach was to use a scoring methodoligy used for chess and apply that ranking system over the entire season and then run a logistic model based on weighted score values.

[`GenerateBracketExample`](https://github.com/bspeiffer/MarchMadness2018/tree/master/GenerateBracketExample) - was a cool example that we found that spits out a prefilled out bracket in the cmd line.

[`Logistic Regression on SeedDiff`](https://github.com/bspeiffer/MarchMadness2018/tree/master/Logistic%20Regression%20on%20SeedDiff) - This was an approach that only took Seed into account and was the first example that we put together so everyone had a place to start from.

## Predictions

[`ELO March Madness.ipynb`](https://github.com/bspeiffer/MarchMadness2018/blob/master/DataPrep_EloFunc_InitialCleanData/ELO%20March%20Madness.ipynb) - This is where all the work was done to prep the data for predictions and generates all the possible game predictions for all the teams in the tournament.

[`March_Madness_Prediction_2018.csv`](https://github.com/bspeiffer/MarchMadness2018/blob/master/DataPrep_EloFunc_InitialCleanData/predictions/March_Madness_Prediction_2018.csv) - This is the raw output from the notebook above.

[`March_Madness_Prediction_2018.xlsx`](https://github.com/bspeiffer/MarchMadness2018/blob/master/DataPrep_EloFunc_InitialCleanData/predictions/March_Madness_Prediction_2018.xlsx) - This excel has the games that were used in the submitted bracket highlighted and is what was used to fill out the bracket for that season.
