# Algorithms and Big Data in Chemistry and Materials
    Hometask #1
1. Upload qm9.csv dataset on your server
2. Find your personal random state in the “students list” table
3. Sample 20k rows from qm9 dataset using your personal random state
   Hometask #2
1. For your dataset get 1000+ descriptors from 2+ sources: RDKit, Pubchem, Mordred, etc. 
2. Select features from downloaded based on at least 2 selection techniques.
    Hometask 3
1. Clear the dataset obtained in the previous stages in accordance with the steps from the lecture
2. Perform data analysis (optional)
3. Choose a method and perform normalization
    Hometask 4:
1. Choose one linear and one non-linear dimension reduction method
2. Run them on your data (It is preferable to use seaborn and plotly to visualize results)
3. Justify the choice of the number of components / dimensions and explain them
    Hometask 5:
1. Choose more than one clustering algorithm (you can use any algorithm you can find, but it should be appropriate for your data and initial assumptions)
2. Run them on your data and visualize (You can make classes from target value to check the quality of your results)
3. Try to find some interesting patterns in your data if possible.
OR you can have bonus points if you can show code for any clustering algorithm from scratch with all the math (except default K-Means)A
    Hometask 6:
1. Choose 3-4 regression models (e.g., LightGBM, XGBoost) and train them to predict “Gap” target variable on default parameters (use 10-fold cross-validation)
Note: every model has use example on scikit-learn.org
2. Visualize the results via R2 plot (predicted vs. real), compare the models’ performance and training speed
3. Optimize the best-performing model using hyperparameters tuning (grid search)
