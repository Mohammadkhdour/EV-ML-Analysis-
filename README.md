# 🚗 EV Population Data - Machine Learning Analysis  

## 📌 Project Overview  
This project explores a **real-world dataset on Electric Vehicle (EV) registrations** using **Machine Learning (ML) techniques**. The dataset includes key attributes such as **vehicle make, model, electric range, location, and registration details**. The goal is to clean the data, analyze trends, and derive meaningful insights using **Exploratory Data Analysis (EDA)** and visualization techniques.  

## 🎯 Objectives  
- 📊 **Data Preprocessing**: Handle missing values and clean data.  
- 🔢 **Feature Engineering**: Encode categorical features for analysis.  
- 📈 **Exploratory Data Analysis (EDA)**: Identify trends and correlations in EV adoption.  
- 🗺️ **Geospatial Analysis**: Analyze EV distribution across locations.  
- 🔍 **Visualization**: Generate insights through plots and charts.  

## 📂 Dataset Description  
The dataset consists of **210,166 samples** and **17 features**, including:  
- **VIN (Vehicle Identification Number)**: Unique identifier for each vehicle.  
- **Location**: City, county, state, and postal code of registration.  
- **Model Details**: Manufacturer, model, and model year.  
- **EV Type**: Battery Electric Vehicle (BEV) or Plug-in Hybrid (PHEV).  
- **Electric Range**: Maximum miles the EV can travel on electric power.  
- **Base MSRP**: Suggested retail price of the EV.  
- **Clean Alternative Fuel Vehicle (CAFV) Eligibility**: Incentive eligibility indicator.  
- **Electric Utility**: The power company servicing the area.  

## 🏗️ Data Cleaning & Preprocessing  
✅ **Handling Missing Values**:  
- Identified missing values and applied **median, mean, and mode imputation**.  

✅ **Feature Encoding**:  
- Used **One-Hot Encoding** to transform categorical variables into numerical format.  

✅ **Normalization**:  
- Applied **Min-Max Scaling** to numerical features to standardize the range.  

## 🔬 Exploratory Data Analysis (EDA)  
📊 **Descriptive Statistics**:  
- Summary statistics were calculated to understand the distribution of features.  

🗺️ **Geospatial Analysis**:  
- Mapped the distribution of EVs across different locations to identify adoption trends.  

📈 **EV Model Popularity**:  
- Identified the **top 10 most popular EV models**, with **Tesla Model Y and Model 3** dominating the market.  

📉 **Temporal Trends**:  
- Analyzed **EV adoption over time**, showing a rapid increase post-2015.  

📌 **Correlation Analysis**:  
- Explored relationships between **electric range, model year, and MSRP**.  

## 📊 Data Visualization  
The following visualizations were created:  
- **Histograms**: Distribution of model years and electric ranges.  
- **Scatter Plots**: Correlation between **electric range vs. model year**.  
- **Heatmaps**: Correlation matrix between numerical features.  
- **Bar Charts**: Popular EV models and distribution by city.  
- **Line Graphs**: Temporal trends in EV adoption.  

## 🔧 Prerequisites  
Ensure you have the following installed:  
- **Python 3.8+**  
- **Jupyter Notebook**  
- **Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn**  

To install dependencies, run:  
```sh  
pip install pandas numpy matplotlib seaborn scikit-learn  
```

## 🚀 Clone the Repository  
To download and set up the project locally, use the following commands:  
```sh  
git clone https://github.com/yourusername/EV-ML-Analysis.git  
cd EV-ML-Analysis  
```

## ▶️ Running the Project  
1. Open Jupyter Notebook:  
   ```sh  
   jupyter notebook  
   ```  
2. Run **ML.ipynb** and execute the cells to see the results.  

## 🔍 Results & Insights  
📌 **Tesla leads the market** with the most registered EVs.  
📌 **EV adoption has increased significantly after 2015**, peaking in 2022.  
📌 **Geographical distribution** shows high EV adoption in urban areas.  

## 🤝 Contributing  
Contributions are welcome! Please fork this repository and submit a **Pull Request**.  

## 📜 License  
This project is licensed under the **MIT License**.  


