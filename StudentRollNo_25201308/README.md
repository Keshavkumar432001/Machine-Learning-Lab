Q1. (K-Means): Add a 3D clustering variant (Income, Spending, Age); visualize in 2D projections. 

        We picked K-Means clustering because it's simple to use, works well, and is great for putting customers into groups.
        We picked three things (Age, Income, and Spending Score) to show trends in behavior and demographics.
        Standardization was used to make sure that all the features added the same amount.
        Five clusters were chosen because that's what people usually do when they divide up stores.
        The silhouette score was used to check the quality of the clusters. 
        We used 2D projections to help us get a better idea of 3D clusters.

Q2. (Linear Regression) –: Multi-variate regression; check multicollinearity via correlation heatmap; report MAE.

       We picked linear regression because the target variable can take on any value.
       To find out how advertising affects people over time, several independent variables were used.
       To find multicollinearity between the predictors, a correlation heatmap was made.
       The train-validation split makes sure that the performance test is fair.
       We chose Mean Absolute Error because it shows an error in the original units that is easy to understand.
       The model is easy to understand, simple, and works well for basic regression analysis.

Q3. (ID3 concept) –: Build a tree with entropy; manually compute information gain for 1 chosen split (one feature) and compare with sklearn’s chosen root split. 

      The ID3 algorithm used entropy to divide things up.
      We manually calculated Information Gain to see how uncertainty goes down after a split.
      The "Sex" feature had the most Information Gain, which means it does the best job of separating classes of people who survive.
      We used a shallow decision tree (max_depth=1) so that the root split would be easy to see.
      The entropy-based decision tree from sklearn picked the same root feature, which confirmed the manual calculation.
      The binary classification problem made accuracy the best way to measure performance.