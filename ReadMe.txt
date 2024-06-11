
---

# Electric Vehicles Data Analysis

## About

This project aims to explore electric vehicle (EV) data to understand top-performing models, efficiency trends, and other key performance metrics. The goal is to study how EV features can be optimized and to provide insights into consumer preferences.

## Dataset Information

The dataset contains information on various electric vehicles. It includes the following columns:

| Column               | Description                          | Data Type       |
|----------------------|--------------------------------------|-----------------|
| Battery              | Battery capacity (kWh)               | FLOAT           |
| Car_name             | Name of the car                      | VARCHAR(255)    |
| Car_name_link        | Link to car details                  | VARCHAR(255)    |
| Efficiency           | Efficiency (Wh/km)                   | FLOAT           |
| Fast_charge          | Fast charging capability (kW)        | INT             |
| Price_DE             | Price in Germany (Euros)             | DECIMAL(10, 2)  |
| Range_               | Range (km)                           | INT             |
| Top_speed            | Top speed (km/h)                     | INT             |
| Acceleration_0_100   | Acceleration time (0-100 km/h)       | DECIMAL(4, 1)   |

## Analysis List

### Basic Analysis

1. **Top 5 cars with the longest range.**
2. **Cars with the highest efficiency.**
3. **Cars with the fastest acceleration (0-100 km/h).**
4. **Average range, efficiency, and price of the cars.**
5. **Maximum and minimum range of the cars.**
6. **Count of cars by top speed range.**
7. **Total count of cars by manufacturers.**

### Specific Analysis

1. **Cars with a range greater than 400 km and price less than 50,000 euros.**
2. **Details of Tesla cars in the dataset.**

### Advanced Analysis

1. **Top 10 cars with the highest efficiency and their corresponding range.**
2. **Cars with fast charging capability (more than 600 kW).**
3. **Cars with a range between 300 and 400 km and top speed above 200 km/h.**
4. **Average acceleration time for cars grouped by manufacturers.**
5. **Cars sorted by their battery capacity (descending order).**
6. **Count of cars by their efficiency ranges.**
7. **Cars with the longest range per price (range divided by price).**
8. **Cars with a range greater than the average range and a price less than the average price.**
9. **Comparison of the average range, efficiency, and price between different vehicle types (e.g., sedans, SUVs, hatchbacks).**
10. **Comparing top speeds of cars by manufacturers.**

### Statistical Analysis

1. **Calculating the standard deviation of range and price.**
2. **Cars with a range greater than 400 km and efficiency higher than 150.**
3. **Top 5 cheapest cars with a range greater than 300 km.**
4. **Finding the median of the battery capacity.**


---