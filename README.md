# Missing value imputation

Here, we present a systematic spproach to evaluate strategies to replace or impute incomplete data. 
- Data: North Atlantic physics and biogeochemistry
- Methods: Mean, KNN, MissForest, GAIN

## Execution order and short notebook description
1. grid.ipynb &#8594; Define and describe the data grid. Perform test-train splits (multiple folds).
2. imputation_tuning.ipynb &#8594; Run experiments to find optimal hyperparameters for each model by a custom grid search.
3. imputation_tuning_evaluate.ipynb &#8594; Evaluate tuning experiments. Save optimal hyperparameters per imputation method.
4. imputation_training.ipynb &#8594; Train models with optimal hyperparameters. Store models.
5. generate_test_files.ipynb &#8594; Generate and store data grids with different patterns of missing values.
6. imputation_testing.ipynb &#8594; Conduct several experiments to evaluate imputation performance.
7. imputation_testing_evaluate.ipynb &#8594; Evaluate test experiments.