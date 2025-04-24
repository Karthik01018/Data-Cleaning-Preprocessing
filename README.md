# Data-Cleaning-Preprocessing
Steps Performed:
Data Import
Loaded the dataset using pandas and performed an initial inspection.

Handling Missing Values

Filled missing numerical values (e.g., Age) using the median.

Categorical features like Cabin and Embarked were filled using 'Unknown' and mode, respectively.

Categorical Encoding

Applied Label Encoding to binary features like Sex.

Used One-Hot Encoding for multi-class categorical features such as Embarked.

Simplified Cabin by extracting the deck letter.

Feature Scaling

Standardized all numerical features using StandardScaler to ensure zero mean and unit variance.

Outlier Detection & Removal

Visualized outliers with boxplots using Seaborn.

Removed outliers from numerical columns using the Interquartile Range (IQR) method.
