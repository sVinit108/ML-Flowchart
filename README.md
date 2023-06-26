# ML-Notes

Imp Phases:-
1. Data Collection 
2. Data Integration
3. Feature Engineering
    - EDA (Num-Cat sep, Distribution analysis, Missing val analysis, Outlier analysis, Feature relation study)
    - Missing Values (Num:- MCAR - 3M Impute,less distort in var,wont work in all cas, MNAR-cap nan, end dis imput, MAR-arbitary val)
       Num - 3M, Arbit, EOD, New F, M freq, Random (from avail vals)
                     (Cat:- "miss", cap nan, fill with most freq)
      Cat - "Miss", New F, Predcit, Unsuper (cls=no of features), M freq
    - Outliers (Detect - Violin plot, 10-90 percentile, Replace with 10,90 percentile)
    - Encoding
    - Scaling
    - Imbalaced
4. Feature Selection
    - Univariate
    - Correlated Features
    - Random forest
5. Model Creation 
   - Lin Reg
   - Log Reg
   - KNN
   - DT
   - RF
   - AdaBoost
   - Gradient Boost
   - XgBoost
   - SVM
   - DBscan
   - K-means
   - Hierarch
6. Cross Validation
   - Train-test
   - K-fold
   - Straified K-fold
   - Random
   - LOOCV
7. Hyperparameter tuning
    - Grid Search
    - RandomsiedCV
    - Genetic Algo
    - Bayesian Opt
