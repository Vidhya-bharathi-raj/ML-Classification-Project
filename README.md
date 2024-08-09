# ML-Classification-Project

# **1. Data Cleaning and Preprocessing**:

- Imported common libraries like numpy, pandas, matplotlib, and seaborn for performing data analysis and visualization.

![](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034015.png))

- Null values were assessed using isnull().sum(), and decisions were made regarding dropping rows or imputing missing data (mean, median, mode).

![](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034027.png)

![](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/ML%20Classification%20Project%20Image/Screenshot%202024-08-01%20034050.png)

- Descriptive statistics (e.g., mean, median, standard deviation) from describe() provided insights into data distribution.

![](https://github.com/Vidhya-bharathi-raj/Project-Images/blob/main/Excel%20Project%20Image/Screenshot%202024-04-09%20015411.jpg)

# **2. Visualization and Analysis**:

- Count plots (Seaborn’s countplot were used for categorical variables (gender, customer type, travel type).

![Screenshot 2024-08-01 034121.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5c1ef36-0975-46c1-ad51-974843803b44/748d8425-caf3-42f2-9a23-39738d195711/Screenshot_2024-08-01_034121.png)

![Screenshot 2024-08-01 034213.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5c1ef36-0975-46c1-ad51-974843803b44/5b20fb36-9436-458d-a02a-b18a811ce2e0/Screenshot_2024-08-01_034213.png)

![Screenshot 2024-08-01 034228.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5c1ef36-0975-46c1-ad51-974843803b44/2fc99f5c-ce97-46f1-8b85-6ce7eaf322cd/Screenshot_2024-08-01_034228.png)

- Histograms revealed continuous variable distributions (e.g., age).

![Screenshot 2024-08-01 034242.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5c1ef36-0975-46c1-ad51-974843803b44/529708b8-81a6-4442-96ae-6656e3dbcf00/Screenshot_2024-08-01_034242.png)

- Catplots explored cleanliness ratings’ impact on satisfaction.

![Screenshot 2024-08-01 034255.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5c1ef36-0975-46c1-ad51-974843803b44/03978279-e685-4593-ae08-a4f88ae29b9f/Screenshot_2024-08-01_034255.png)

- Count plots showed satisfaction counts by class type.

![Screenshot 2024-08-01 034314.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5c1ef36-0975-46c1-ad51-974843803b44/21e11909-15af-4fdb-9767-3efac1e148a6/Screenshot_2024-08-01_034314.png)

# **3. Feature Encoding and Correlation**:

- Categorical features were encoded (one-hot or label encoding) for modeling.

![Screenshot 2024-08-01 034324.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5c1ef36-0975-46c1-ad51-974843803b44/ae714c67-5fc0-457e-a289-d8bc6a7d810c/Screenshot_2024-08-01_034324.png)

- Feature correlations were visualized with a heatmap.

![download.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5c1ef36-0975-46c1-ad51-974843803b44/e2b3eebd-d5fa-4cc9-8a25-ea5ed0ea8fef/download.png)

- Features were sorted based on correlation values.

![Screenshot 2024-08-02 144157.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5c1ef36-0975-46c1-ad51-974843803b44/9a8715dc-21e6-47ef-87e5-7b21441688be/Screenshot_2024-08-02_144157.png)

# **4. Machine Learning**:

- Data was split into features (X) and target (y).

![Screenshot 2024-08-01 034414.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5c1ef36-0975-46c1-ad51-974843803b44/26d20100-d654-4e60-9a9c-3b5278f15587/Screenshot_2024-08-01_034414.png)

- A model was built and evaluated using classification metrics.
