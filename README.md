The quest is to model more robustly the Sklearn's diabetes dataset. Quite cranky, but thus far the quest taken 4 attempts:

First attempt: The diabetes dataset was split, modelled and evaluated with 6 models using the basic train_test_split approach.

Second attempt: Use of cross-validation(CV) across 6 models to get better model performance on the dataset.

Third attempt: In addition to CV, dropped 2 very low importance features; decision informed through analysis of feature importances and possible interactions. File attached(TestForInteraction.ipynb)

Fourth attempt: Adding to step 3 above, created 3 new interaction features; interactions determined through analysis of feature interactions. File attached(TestForInteraction.ipynb)

See the datasets.ipynb file in master branch for 1st attempt, in Testing_CV for 2nd attempt, and in Testing_Interactions for 3rd and 4th attempts.
See the Analysis & summary file for quest results.

Welcome!
