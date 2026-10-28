# 🚦 Road Traffic Accident Analysis and Severity Prediction

## 📌 Project Overview

Road traffic accidents are a major safety concern. Understanding the factors associated with accidents can help identify patterns and support better road safety planning.

This project analyzes road traffic accident data using Python and Exploratory Data Analysis (EDA). It explores accident severity, driver characteristics, vehicle details, road conditions, weather conditions, and casualty information to discover meaningful patterns and relationships.

The project introduces the goal of predicting accident severity across three categories: Slight Injury, Serious Injury, and Fatal Injury. The current documented work focuses primarily on data cleaning, data manipulation, and exploratory analysis.

## 🎯 Project Objectives

- Analyze road traffic accident data and severity patterns.
- Understand the relationship between driver characteristics and accident records.
- Examine vehicle types and the number of vehicles involved.
- Study road surface, lighting, and weather conditions.
- Analyze casualty counts across different accident severity categories.
- Explore accident patterns across days of the week and driving experience.
- Generate insights to support road safety and accident prevention.

## 🛠️ Technologies and Tools

- **Python:** Main programming language.
- **Pandas:** Data cleaning, manipulation, and analysis.
- **NumPy:** Numerical operations.
- **Matplotlib:** Data visualization.
- **Seaborn:** Statistical charts and plots.
- **Feature-engine:** IQR-based outlier treatment.
- **Jupyter Notebook:** Interactive development and analysis.

## 📂 Dataset Information

The dataset contains **12,316 records and 32 columns** related to road traffic accidents.

### Important Features

| Feature | Description |
|---|---|
| `Time` | Time when the accident occurred |
| `Day_of_week` | Day of the accident |
| `Age_band_of_driver` | Driver age category |
| `Sex_of_driver` | Driver gender category |
| `Driving_experience` | Driver's experience category |
| `Type_of_vehicle` | Vehicle involved in the accident |
| `Road_surface_conditions` | Condition of the road surface |
| `Light_conditions` | Lighting conditions |
| `Weather_conditions` | Weather during the accident |
| `Cause_of_accident` | Recorded cause of the accident |
| `Number_of_vehicles_involved` | Number of vehicles involved |
| `Number_of_casualties` | Number of casualties |
| `Accident_severity` | Slight, serious, or fatal injury |

**Dataset Source:** [Accident Prediction Dataset – Kaggle](https://www.kaggle.com/datasets/adityaakuskar/accident-prediction-dataset)

## 🔄 Project Workflow

### 1. Data Understanding
- Loaded the dataset using Pandas.
- Examined dataset dimensions, column names, and data types.
- Used descriptive statistics to understand numerical features.

### 2. Data Cleaning
- Identified missing values in different columns.
- Filled missing numerical values using the median.
- Filled missing categorical values using the mode.
- Checked for duplicate records.
- Identified and treated outliers in numerical data.
- Corrected inconsistent spaces, capitalization, and category labels.
- Verified numerical data types after cleaning.

### 3. Data Manipulation
Used Pandas functions to filter, select, and summarize accident records.

Key operations include:
- `loc` and `iloc`
- `at` and `iat`
- `query()`
- `groupby()`
- `value_counts()`
- `pivot_table()`
- `crosstab()`

### 4. Exploratory Data Analysis (EDA)

**Univariate Analysis**
- Histograms
- KDE plots
- Boxplots
- Count plots
- Pie charts

**Bivariate Analysis**
- Scatterplots
- Barplots
- Line charts
- Strip plots
- Violin plots
- Cross-tabulations

**Multivariate Analysis**
- Correlation heatmaps
- Pair plots
- Joint plots

These visualizations help explore individual variables and relationships between accident-related factors.

## 📊 Key Findings

- Slight-injury accidents are the most frequent category in the dataset.
- Most recorded accidents involve a relatively small number of vehicles.
- Fatal-injury cases have a higher average casualty count than serious- and slight-injury cases.
- Accident records vary across days of the week.
- Road surface and weather conditions provide useful categories for examining accident patterns.
- The relationship between vehicle involvement and casualty counts can be explored through scatterplots and correlation analysis.

## 💡 Business Applications

The findings from this project may help to:

- Identify accident patterns that require further investigation.
- Support road safety awareness programs.
- Improve understanding of accident-related environmental conditions.
- Support traffic management and road safety planning.
- Inform future research into accident severity prediction.

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn feature-engine jupyter
   ```

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the project `.ipynb` file.
5. Update the dataset path to the location of your CSV file.
6. Run the notebook cells in order.

## 📁 Project Structure

```text
road-accident-severity-analysis/
│
├── README.md
├── road_accident_analysis.ipynb
├── RTA Dataset.csv
└── Activity 2.pdf
```

*Replace the example filenames with your actual filenames. Include the dataset only if its license permits redistribution.*

## 🏁 Conclusion

This project demonstrates how Python can be used to clean, manipulate, and analyze road traffic accident data. Through exploratory data analysis and visualization, it explores patterns involving accident severity, driver characteristics, vehicles, road conditions, weather, and casualties.

The insights can support further investigation into accident prevention and road safety. A trained machine-learning model would be a separate next step for completing the accident severity prediction objective.

## 👨‍💻 Author

**Veda Vedya Ram**

GitHub: [@vedavedyaram](https://github.com/vedavedyaram)

