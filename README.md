# Sales-Analysis-in-Tech
I used Python to combine 12 months of sale data into 1 file, speciliasing in thousands of electronics. It included Order ID, Order Date, Price, Quantity Ordered, Purchase Address, etc.

# 📩 Tasks
First of all, I cleaned the data 
- by removing NAN, null value and duplicated Order ID
- change the type of columns ( to_numeric, to_datetime, astype)

# 🎯 Insights
I explored 5 business questions related to the data
1. What was the best month for sales? How much was earned that month?
2. What city sold the most products?
3. What time should we display adverstisements to maximize the likelihood of customer's buying product?
4. What products are most often sold together?
5. What product sold the most?

To answer all above questions, pandas, datetime and matplotlib methods were imported in Python to help me to analyse the data. It consisted of:
- combining multiple .csv file to create a new Dataframe
- adding to column (Month and City column) by extracting data
- using the .apply() method
- using groupby to perform aggregate analysis
- plotting bar chart to make a visualisation

# Let's check out the detailed description 👉

