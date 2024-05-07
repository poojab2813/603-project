### Spark-based Climate Change Analysis

**Objective:**  
- Analyze climate data from different meteorological stations.  
- Explore temperature distribution patterns, precipitation, wind speed, and other weather parameters.  
- Load data efficiently with Apache Spark.


**steps to run the project:**  
1. Open the project notebook or script file to access all the code and analysis steps.
2. **Load the Dataset:** Load the weather dataset using Spark. Display the first few rows using df_weather.show(5).
3. **Data Cleaning:**
   - Count the rows with df_weather.count() to ensure data is loaded properly.
   - Proceed with data cleaning, removing or filling missing values, and ensuring that data types are accurate.
   - Impute Missing Values Replace “NA” data in HourlyDryBulbTemperatureF and HourlyRelativeHumidity columns with 0 using the .na.fill method. Build a Data Imputer    - From PySpark, import the Imputer class, then use this class to set up a median-value imputer for the temperature and humidity columns, which will fill in all 
      missing values.
4. **Create a pipeline:**
    - Incorporate other feature processing tools such as VectorAssembler for merging the preferred variables.
    -  Incorporate an imputer and an assembler into a pipeline for standardize transformation of data and make sure outcomes are homogeneous and stable.
5. **Performing EDA for visibilty and weather conditions:**
    - Perform exploratory data analysis (EDA) to find patterns, correlations, and trends.
6. **Machine learning models:**
   - **Logistic Regression:** This model is effective in prediction of chances with two possibilities, such as determining the likelihood for it to rain.
   - ** Neural Network:** A multi-layer perceptron classifier (MLP) implemented that detects underlying nonlinear complex patterns in the data.
   - **Decision Tree Regression:** For regression tasks, decision tree model splits data into branches depending on target variable so as to improve accuracy of predictions.
   - **Support Vector Machine (SVM):** The data was fitted by an SVM model for categorization and prediction in order to determine the best separating hyperplane or boundary.
     







