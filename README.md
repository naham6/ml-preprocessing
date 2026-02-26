## Approach 1: Standard One-Hot Encoding & Imputation

- Handled missing values using **median imputation**.
- Applied **One-Hot Encoding** to categorical variables.
- Resulted in **68 total features** after encoding.

---

## Approach 2: Feature Engineering (Polynomial Interactions)

- Generated new interaction terms between existing features using **PolynomialFeatures**.
- Expanded the dataset to **over 1,700 features**.
- Designed to capture complex, non-linear relationships.

---

## Approach 3: Label Encoding & Custom Cleaning

- Applied domain-specific logic to clean missing data  
  - Example: inferring sex from relationship status.
- Used **SimpleImputer**:
  - Mean for numerical features  
  - Most frequent for categorical features
- Applied **Label Encoding** to categorical variables instead of One-Hot Encoding.
