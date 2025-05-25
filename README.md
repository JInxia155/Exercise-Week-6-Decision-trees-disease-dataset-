Download link https://programming.engineering/product/exercise-week-6-decision-trees-disease-dataset/

Be prepared for the exercise sessions (watch the demo lecture). You may ask TAs to help if you cannot make your program to work, but don’t expect them to show you how to start from the scratch.

    Disease { Scikit-Learn regressors (40 points)

Download data about measuring severity of a certain disease (the larger is the value the worse is the case).

        disease train.txt

        disease X test.txt

        disease y train.txt

        disease y test.txt

    Baseline (10 points)

Compute regression baseline by using the training data mean value as the prediction for all test samples.

Print baseline MSE.

Note: You can use MSE available in the sklearn.metrics sub-package.

    Linear model (10 points)

Use sklearn.linear model to t a linear model to the data.

Use the linear model to predict the values for the test data and print the test set MSE.

    Decision tree regressor (10 points)

Use sklearn.tree.DecisionTreeRegressor to t a decision tree to your data. Use the model to predict the values for the test data and print the test set MSE.

    Random forest regressor (10 points)

Use sklearn.ensemble.RandomForestRegressor to t a random forest to your data.

Use the model to predict the values for the test data and print the test set MSE.

Return the following items:

    Python code (single le): <surname> disease.py

    A full desktop screenshot that includes a terminal window executing your code and printing each method name and the obtained MSE:

<surname> disease desktop.png

1

