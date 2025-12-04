
# Food Delivery Trend Analysis

A beginner-friendly data analytics project exploring factors that influence food delivery performance.  
This project includes **data cleaning**, **exploratory analysis**, and a **Power BI dashboard**.


## Project Goals
- Understand what affects delivery time  
- Identify trends in customer orders  
- Analyze how personell, age of personnel, vehicle, delivery time and restaurant ratings, etc. influence service  
- with a simple dashboard to communicate insights  (Power Bi) 


## Dataset
Source: Kaggle – *Food Delivery Dataset*  


### Key Features:
- `ID`
- `time_taken(min)`
- `restaurant_latitude`
- `restaurant_longtitude`
- `delivery_person_ID`
- `delivery_person_age`
- `delivery_person_ratings`
- `delivery_location_latitude`
- `delivery_location_longtitude`
- `type_of_order`
- `type_of_vehicle`


## Data Cleaning and Preprocessing Steps
initial status of data: 
- 45 539 and 11 columns
- Removed duplicate rows  
- Fixed column names  
- Handled missing values by using median age to preserve the overall distribution (delivery_person_age)
- Checking for & correcting inconsistent data formats, e.g. delivery_person_ratings was treated as a numeric float
- Detected and treated outliers: Examining the target variable, e.g. time_taken(min)
  
key insights for modelling:
- Age and Ratings (average delivery person age is between 25 and 35, drivers with 4,8+, deliveries take mostly 25min.)
- categorical encoding: E.g type_of_vehicle
Python file: **FinalProject_deliverytime.ipynb**


## Exploratory Data Analysis

Main insights:
- Evening hours = highest order volume   
- Longer distances strongly correlate with delays  
- Higher-rated restaurants deliver faster  

Jupyter notebook: **EDA.ipynb**


## Power BI Dashboard
Included insights:
- Average delivery time vs Type of vehicle
- Sum Restaurant latitude vs Sum Restaurant longitude of Time taken(min) vs
  Type of order and Type of vehicle
- Distance vs. Delivery time

File: **dashboard.pbix**


## Tools Used
- Python (Pandas, Seaborn, Matplotlib)  
- Jupyter Notebook  
- Power BI 


## Author
**Akouvi Selom Alex**  
@ReDI school for Integration, Munich
2025 Final Project, Munich, Germany  

