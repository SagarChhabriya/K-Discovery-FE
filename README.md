# Feature Engineering
1. Feature Transformation  (FT)
2. Feature Construction    (FC)
3. Feature Selection       (FSe)
4. Feature Extraction      (FE)
<hr>

1. **Feature Transformation** <br>
    1. Missing Value Imputation (Remove Missing Values | Impute Missing Values)<br>
        - Remove (drop) <br>
        - Impute (CCA: Complete Case Analysis) <br>
            - Univariate Imputation (Use When MCAR: Missing Completely at random ) <br><br>
                a. Numerical <br><br>
                    - Mean/median<br>
                    - Random<br>
                    - End of Distribution (NMAR: Not missing at Random)<br><br>
                b. Categorical<br><br>
                    - Mode<br>
                    - Missing (indicator)<br><br>
            - Multivariate Imputation<br><br>
                - KNN imputer <br>
                - Iterative Imputer <br>
                - MICE (Multivariate Imputation by Chained Equations)<br><br>
                
    1. Handling Categorical Features (Encoding Categorical Data)<br><br>
        1. Oridnal Encoding <br>
        1. One Hot Encoding<br>
            - sklearn ColumnTransformer<br> 
        1. Label Encoding<br><br>

    1. Outlier Detection (Techniques for outlier detection and removel) <br><br>
            1. Z-score treatment (Normal or almost Normal distribution)<br>
            2. IQR Based filtering (skewed distribution)<br>
            3. Percentile<br>
            4. Winsorization<br> <br>
        
    1. Feature Scaling (FS)<br><br>
        1. Standardization (Also called as Z-score Normalization)<br>
            - sklearn StandardScalar<br><br>
        2. Normalization<br>
            a. Min Max Scaling <br> 
            b. Mean Normalization <br>
            c. Max Absolute Scaling <br>
            d. Robust Scaling <br>
    1. Mathematical Transformations (For Normal Distribution)<br><br>
        1. Function Transformer<br>
            - Log Transformation<br>
            - Reciprocal Transformation<br>
            - Squaure | Square Root<br>
            - Custom<br>
        1. Power Transformer<br>
            - Box-Cox Transformation<br>
            - Yeo-Johnson Transformation<br><br>
        1. Quantile Transformer
1. **Feature Selection**<br>
    1. Forward Selection<br>
    1. Backward Elimination<br>
1. **Feature Construction**<br>
    1. PCA (Principle Componenet Analysis)<br>
    1. LDA (Linear Discrimnant Analysis)<br>
    1. tsne <br>

1. **Feature Extraction**<br><br>
    1. PCA (Principle Component Analysis)

MISC<br>
    - Discretization (Binning)<br>
        - Unsupervised Discretization<br>
            - Equal width uniform<br>
            - Equal Frequency (quantile)<br>
            - K-means Binning<br>
        - Supervised<br>
            - DecisionTree Binning<br>
        - Custom Binning<br>
Links<br>
    [Eigendecomposition of Covariance Matrix (visiondummy.com)](https://www.visiondummy.com/2014/04/geometric-interpretation-covariance-matrix/)
