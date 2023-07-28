# Walmart-Sales-Pred
Predicting Walmart store sales using Random Forest

Dataset link:- https://www.kaggle.com/datasets/varsharam/walmart-sales-dataset-of-45stores

Google Colab notebook is linked here:- https://colab.research.google.com/drive/12YRCKG8qh4NkdwsfF9rEBkWTkypopRaW#scrollTo=5rthbwb7HfOs

#About the DataSet 

The file has information about the Weekly Sales of 45 stores for the year 2010-2012 including the factors affectors affecting Sales such as Holidays, Temperature, Fuel Price, CPI, and Unemployment.

Within the Dataset file, following fields are present:
1. Store - the store number
2. Date - the week of sales
3. Weekly_Sales - sales for the given store
4. Holiday_Flag - whether the week is a holiday week 1 – Holiday week 0 – Non-holiday week
5. Temperature - Temperature on the day of sale
6. Fuel_Price - Cost of fuel in the region
7. CPI – Prevailing consumer price index
8. Unemployment - Prevailing unemployment rate


# Conclusion

Here, we tried using 3 different algorithms to understand which model to use to predict the weekly sales.

Linear Regression is not an appropriate model to use as accuracy is very low.

However, Random Forest Regression gives an accuracy of almost 95%. So, it is the best model to forecast weekly sales.
