
# 📊 Sales Forecasting Project 📈
![image alt](https://github.com/SyedAliNice/Sales-forecast/blob/0b5079f32e3ef2918c0d286329493beebbc53795/a-digital-illustration-of-a-modern-busin_QVg0fh3wTVe7nwSta5HEVg_QsHiBmfORbqy_brLBQ3jyg-fotor-20250407121650.jpg)
#   📚 Project Overview
This project focuses on predicting sales across multiple restaurants based on historical sales data. It involves using machine learning and deep learning models to analyze trends and forecast future sales. The primary goal is to help restaurant managers make better business decisions by predicting sales more accurately.

#   🧠 Technologies Used

📘 Python

📗 Pandas, Numpy

   📉 Matplotlib, Seaborn

   🤖 Scikit-learn, XGBoost

   🔥 TensorFlow / Keras (LSTM)

   📁 Jupyter Notebook

#   📊 Data Overview
This project utilizes multiple datasets to predict sales trends across restaurants:

-   sales.csv: Contains transaction-level details (sales volume, item, store).

-   items.csv: Details of items (name, category).

-   restaurants.csv: Restaurant-specific details (location, attributes).

The datasets are merged into a consolidated dataset for analysis.

#   🔍 Exploratory Data Analysis (EDA)
**📅 Sales Patterns Over Time**

We analyzed sales trends across days, months, and quarters. Key findings:

-   Sales show clear seasonality, with higher sales in the middle of the year and lower sales in December.

-   Fridays and Saturdays exhibit the highest sales.

**🍽️ Restaurant Performance**

The performance of restaurants was compared:

-   Top-performing restaurants: Bob's Diner, Fou Cher, Corner Cafe.

-   Lowest-performing restaurants: Sweet Shack, Beachfront Bar.

**🍴 Popular Items**

The most popular items include:

-   Top Seller: Strawberry Smoothy

-   Others: Frozen Milky Smoothy, Amazing Pork Lunch.
#   🧠 Forecasting Models
🧮 Machine Learning Models

-   Linear Regression: A baseline model, which was the least accurate.

-   Random Forest: Achieved the lowest RMSE and highest R², making it the most accurate model.

-   XGBoost: Slightly less accurate than Random Forest, but still performed well.

#   📈 Deep Learning Model (LSTM)

An LSTM model was used for time series forecasting. It performed well in capturing seasonal trends and produced reliable predictions with a MAPE of 37.86%.
 #  📁 Repository Structure
        📁 sales-forecasting/
    ├── 📊 sales_forecast.ipynb  # Main notebook with ML & DL models
    ├── 📁 data/
    ├── sales.csv
    ├── items.csv
    └── restaurants.csv
    ├── 📄 Sales Forecast Report.docx    # Detailed report
    ├── 📄 README.md                     # This file
#   ⚙️ How to Use
1.  Run the analysis in Jupyter Notebook:

-   Open the sales_forecast.ipynb notebook.

-   Execute each cell to perform EDA, train models, and make forecasts.

2.  Review Results:

-   Review graphs for sales trends.

-   Check model performance metrics (RMSE, MAE, R²).
#   📈 Results
🏆 Best Model: Random Forest
-   RMSE: 60.09

-   MAE: 47.77

-   R²: 94.41
#   📄 Conclusion

This project demonstrates the power of machine learning and deep learning models to forecast sales in a dynamic restaurant environment. Random Forest emerged as the top model, and the LSTM model effectively handled the time series data.
