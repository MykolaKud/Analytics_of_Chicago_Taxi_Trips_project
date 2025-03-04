![image](https://github.com/user-attachments/assets/f3dea6c2-156d-4d67-bcc0-fe9886e7aa52)

# Chicago Taxi Trips Analysis

## Overview  
This project analyzes key metrics based on a dataset of Chicago taxi trips. The data was sourced from Google BigQuery's open database.  
The project available in 2 languages:

[Project in English](https://github.com/MykolaKud/Analytics_of_Chicago_Taxi_Trips_project/blob/c26413857fb4843cab606716b1d11ec6eb55696f/Chicago_taxi_project_English.ipynb)

[Project in Ukrainian](https://github.com/MykolaKud/Analytics_of_Chicago_Taxi_Trips_project/blob/c26413857fb4843cab606716b1d11ec6eb55696f/%D0%A1hicago_taxi_project_Ukrainian.ipynb)

## Technologies Used  
- **Google BigQuery** – for data extraction  
- **Google Colab** – for data processing and analysis  
- **Python (Pandas, Matplotlib, Seaborn, etc.)** – for data manipulation and visualization  

## Timeline  
Developed from **December 2024 to January 2025**.  

## Data Source  
Chicago taxi trip data from [Google BigQuery public datasets](https://console.cloud.google.com/marketplace/details/chicago-data-portal/chicago-taxi-trips).  
[Direct link](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1sbigquery-public-data!2schicago_taxi_trips)

## Key Insights  

### Trip Volume Trends  
- The highest workload occurs between **08:00 and 20:00 on working days**.  
- The busiest months are **July, October, and November**, with significantly more trips from **May to December** compared to the first four months of 2021.  

### Fare Patterns  
- The **average fare increased from May to September 2021**, aligning with the rise in trip volume.  
- Most trips from **July to November** had fares higher than the **annual average of $19.49**.  

### Revenue and Payment Methods  
- The highest revenues were recorded from **July to November**, which correlates with the busiest months.  
- **Credit card payments dominate**, though in the low season (January-April), cash and credit card revenues are nearly equal.  
- A significant portion of transactions are categorized as **"unknown payment method,"** especially in the low season, requiring further investigation.  

### Trip Length Trends  
- **Trip lengths tend to increase during summer months and in December-January**, possibly due to holiday travel.  
- The longest trips occurred on **Sunday, January 3rd, after New Year**, and longer trips in January were mostly on weekends, likely due to **church visits, social gatherings, and family events**.  

### Earnings per Mile  
- **Short trips generate the highest earnings per mile**.  
- Since short trips make up the majority of rides, strategies to **increase demand should focus on encouraging short-distance taxi usage**.  

### Tipping Patterns  
- The top five locations by **total tips** are **76, 8, 32, 28, and 56**.  
- For the month with the highest tips, the top locations are **76, 8, 32, 33, and 28**, with the first three locations appearing in both rankings.  

### Speed vs. Tips  
- Passengers tend to **tip more for comfortable, slower rides** rather than fast trips.  
- There is a **moderate negative relationship** between average speed and total tips, indicating that **faster trips receive lower tips**, but the effect is not very strong.  
- The relationship is **statistically significant**, suggesting that **riders value a smoother ride over speed when tipping**.  


## How to Use  
1. Clone the repository  
2. Open the notebook in Google Colab  
3. Run the analysis using the provided dataset  
