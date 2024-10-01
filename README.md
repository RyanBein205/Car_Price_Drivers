# Car_Price_Drivers
What Drives the Price of a Car?

Project Overview
The focus of this project is to explore the pricing trends in the used car market by analyzing various features such as the car's year of manufacture, model, mileage, fuel type, and brand. The insights drawn from this analysis will help used car dealerships make informed decisions regarding their inventory and pricing strategies.

Objectives
Identify the key factors that influence used car prices.
Provide actionable recommendations for pricing and inventory management.
Create visualizations that clearly depict pricing trends across different car attributes.
Dataset
The dataset includes the following key features:

Price: The selling price of the car.
Year: The year of manufacture of the car.
Manufacturer: The car manufacturer (e.g., Toyota, BMW).
Model: The specific model of the car.
Fuel Type: The type of fuel the car uses (e.g., gasoline, electric).
Odometer: The mileage of the car.
State: The U.S. state where the car is located.
Data Cleaning and Preparation
Data cleaning and preparation were crucial to ensure accurate analysis:

Handling Missing Data: We removed columns with over 30% missing values and cleaned rows with missing values in key columns (e.g., price, year, manufacturer).
Outlier Removal: We filtered out extreme price outliers to ensure a more reasonable analysis.
Data Transformation: Numerical columns such as year and odometer were converted to appropriate data types to facilitate analysis.
Exploratory Data Analysis
The exploratory analysis revealed key relationships between car attributes and prices:

Car Price vs Year of Manufacture: Newer cars tend to have higher prices. A scatter plot illustrates this trend clearly.
Car Price vs Mileage: Cars with lower mileage typically have higher prices. We visualized this relationship through a scatter plot of price vs odometer.
Manufacturer Impact: Luxury car brands (e.g., BMW, Mercedes-Benz) command higher prices than mass-market brands (e.g., Ford, Toyota).
Fuel Type Impact: Electric and diesel vehicles are generally more expensive compared to gasoline and hybrid cars.
Example Visualizations:

Car Price Distribution by Manufacturer

![Screenshot 2024-10-01 001619](https://github.com/user-attachments/assets/ff5df578-36b9-4fb7-9673-5b5a146f106b)

Car Price vs Year and Mileage

![Screenshot 2024-10-01 001601](https://github.com/user-attachments/assets/1e079241-0abc-48de-bd55-a4215e21169d)


Insights and Conclusions
Based on our analysis, we can conclude:

Electric and Diesel Vehicles: These tend to have higher resale values, making them valuable for dealerships to stock.
Luxury Brands: Brands like BMW and Mercedes-Benz consistently fetch higher prices, and thus, focusing on these manufacturers can lead to higher profit margins.
Mileage and Year: Lower mileage and newer models are key factors in determining higher prices. Dealerships should consider these factors when acquiring inventory and setting prices.
How to Use
Prerequisites
To replicate the analysis:

Install the necessary Python libraries (pandas, seaborn, matplotlib) using pip install -r requirements.txt.
Clone this repository to your local machine.
Running the Notebook
Open the notebook.ipynb in your preferred environment (e.g., Jupyter Notebook).
Run the cells in sequence to clean the data, perform exploratory analysis, and visualize the results.
You can view the notebook directly in this repository by clicking [Jupyter Notebook](Car-Analysis.ipynb).

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Kaggle for providing the dataset.
All contributors to the open-source libraries used in this project.
