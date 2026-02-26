Approach 1: Standard One-Hot Encoding & Imputation

Handled missing values using median imputation.

Applied One-Hot Encoding to categorical variables, resulting in 68 features.

Approach 2: Feature Engineering (Polynomial Interactions)

Generated new interaction terms between existing features using PolynomialFeatures.

Expanded the dataset to over 1,700 features to capture complex, non-linear relationships.

Approach 3: Label Encoding & Custom Cleaning

Applied domain-specific logic to clean missing data.

Used SimpleImputer (most frequent/mean) for remaining missing values.

Applied Label Encoding to categorical variables instead of One-Hot Encoding.
