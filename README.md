# ML-Classification-Project

# **1. Data Cleaning and Preprocessing**:

- Imported common libraries like numpy, pandas, matplotlib, and seaborn for performing data analysis and visualization.

![](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034015.png))

- Null values were assessed using isnull().sum(), and decisions were made regarding dropping rows or imputing missing data (mean, median, mode).

![](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034027.png)

![](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034050.png)

- Descriptive statistics (e.g., mean, median, standard deviation) from describe() provided insights into data distribution.

![](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-02%20143005.png)

# **2. Visualization and Analysis**:

- Count plots (Seaborn’s countplot were used for categorical variables (gender, customer type, travel type).

![](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034121.png)

![Screenshot 2024-08-01 034213.png](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034213.png)

![Screenshot 2024-08-01 034228.png](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034228.png)

- Histograms revealed continuous variable distributions (e.g., age).

![Screenshot 2024-08-01 034242.png](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034242.png)

- Catplots explored cleanliness ratings’ impact on satisfaction.

![Screenshot 2024-08-01 034255.png](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034255.png)

- Count plots showed satisfaction counts by class type.

![Screenshot 2024-08-01 034314.png](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034314.png)

# **3. Feature Encoding and Correlation**:

- Categorical features were encoded (one-hot or label encoding) for modeling.

![Screenshot 2024-08-01 034324.png](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034324.png)

- Feature correlations were visualized with a heatmap.

![download.png](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/download.png)

- Features were sorted based on correlation values.

![Screenshot 2024-08-02 144157.png](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-02%20144157.png)

# **4. Machine Learning**:

- Data was split into features (X) and target (y).

![Screenshot 2024-08-01 034414.png](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034414.png)

- A model was built and evaluated using classification metrics.
