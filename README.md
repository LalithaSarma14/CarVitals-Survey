# CarVitals-Survey
The CarVitals Survey Dashboard is an interactive Excel-based analytics tool designed to visualize and analyze survey responses related to vehicle dashboard indicators and performance metrics. This dashboard helps users gain insights into common on average price of the car, engine size, car type, miles and ownership.
# Dashboard
![image alt](https://github.com/LalithaSarma14/CarVitals-Survey/blob/87e10f65d6dc9885110ef6e02eaa372dbd5a1a01/car_dashboard_overall.png)
## 1. Data Overview
This project analyzes a dataset containing key specifications of various car models, focusing on brand, model, year, engine size, fuel type, transmission, mileage, doors, owner count, and price. The dataset provides insights into how these factors influence vehicle pricing and ownership trends.

### Dataset Features:
- Brand: Represents the car's brand along with the model name.
- Model: Specifies the exact model of the vehicle.
- Year: Indicates the manufacturing year, ranging from 2000 to 2024.
- Engine Size: The engine capacity in liters, ranging from 1.0L to 5.0L, increasing in increments of 0.1L.
- Fuel Type: Categorized into Petrol, Diesel, Hybrid, and Electric.
- Transmission: Represents the type of transmission, such as Manual, Automatic, or CVT.
- Mileage: The total distance the car has traveled, measured in miles or kilometers.
- Doors: The number of doors in the vehicle, which can be 1, 2, 3, 4, or 5.
- Owner Count: Represents the number of previous owners as a whole number.
- Price: The selling price of the car, expressed in US dollars.
## 2. Data Cleaning
![image alt](https://github.com/LalithaSarma14/CarVitals-Survey/blob/3d2b03ab4f42e5505db2c25fb29f9111b6c1d618/Screenshot%202025-03-02%20125910.png)
- Implemented robust data preprocessing techniques by imputing missing values using median/mode for mileage, price, and fuel type, while eliminating incomplete records in critical fields such as Year, Engine Size, and Transmission, ensuring data integrity.
- Performed comprehensive data validation by standardizing brand and model names, unifying mileage units, and applying logical constraints to ensure accuracy in owner count and pricing.
- Optimized dataset structure by enforcing uniform formatting for categorical features, renaming columns for clarity, and enhancing schema consistency for seamless data integration and analysis.
- Executed advanced data cleansing strategies by identifying and removing duplicate car listings and leveraging statistical methods to detect and eliminate outliers in price, engine size, and mileage, improving overall data quality and reliability.
## 3.Exploratory Data Analysis (EDA)
The dataset was analyzed to uncover patterns and relationships between various car attributes and their impact on pricing
- Average Car Price by Brand and Model – Analyzed brand-wise and model-wise price variations to identify premium vs. budget car brands.
Here the car brands 
![image alt](https://github.com/LalithaSarma14/CarVitals-Survey/blob/e617766a3578d77f50ff42aa86ffa3423b6569a5/1.png)

### Impact of Engine Size on Price  
Examined the correlation between engine size and car price, identifying whether larger engines command higher prices.
 1. Average Car Price by Brand and Model: Analyzed brand-wise and model-wise price variations to identify premium vs. budget car brands.
 - Overall Average Price: The average price across all brands is $8,852.96.
 - Highest Priced Brand: Mercedes ($8,980.09) – Positioned as a premium brand with the highest average price.
 - Lowest Priced Brand: Kia ($8,778.28) – Identified as the most budget-friendly brand.
2. Brand-wise Price Variation
Premium Brands:
- Mercedes ($8,980.09) – Highest-priced due to luxury positioning.
- Audi ($8,923.97) – Slightly lower but remains in the premium category.
- Volkswagen ($8,922.38) – Falls within a similar price range as Audi.
Mid-Range Brands:
- Toyota ($8,895.29) – Positioned slightly above average.
- Ford ($8,852.57) – Closely aligns with the overall average price.
- Honda ($8,865.10) – Offers competitive pricing with models like Civic and Accord.
Budget-Friendly Brands:
- Hyundai ($8,805.20) – More affordable with models like Elantra and Sonata.
- Kia ($8,778.28) – The lowest-priced brand, targeting the budget segment.
3. Key Observations:
- Luxury brands (Mercedes, Audi, Volkswagen) tend to have higher average prices.
- Mid-range brands (Toyota, Honda, Ford) offer a balance of affordability and reliability.
- Budget brands (Kia, Hyundai) have lower prices, making them accessible to cost-conscious buyers.
### Effect of Mileage on Resale Value – Investigated how higher mileage influences depreciation, revealing trends in price reduction with increased usage.
### Most Common Fuel Type – Determined the distribution of cars by fuel type (Petrol, Diesel, Hybrid, Electric) to understand market preferences.
### Fuel Type vs. Price – Explored price differences among fuel types, highlighting whether electric and hybrid vehicles are priced higher than petrol or diesel models.
### Impact of Number of Doors on Price – Assessed whether 2-door vs. 4-door configurations significantly affect car pricing trends.
