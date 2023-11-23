# EDA of Car Prices Using Python

The objective of this EDA project is to gain a comprehensive understanding of a dataset containing information about vehicles, including their pricing. By conducting exploratory data analysis, we aim to uncover insights, patterns, and relationships within the data, which can be valuable for pricing strategies, market research, and decision-making in the automotive industry.

### Dataset Description
* **ID:** Unique Identifier of a vehicle
* **Price:** Price of the vehicle
* **Levy:** Additional cost or fee associated with the purchase of the vehicle.
* **Manufacturer:** The name of the manufacturer or company that produced the vehicle
* **Model:** The specific model name or designation of the vehicle produced by the manufacturer
* **Prod. year:** Production year of the vehicle
* **Category:** Classifies the vehicles into different categories or types
* **Leather interior:** Indicates whether the vehicle has a leather interior
* **Fuel type:** It specifies the type of fuel the vehicle uses, such as "Gasoline," "Diesel," "Hybrid," or "Electric."
* **Engine volume:** It represents the engine's displacement volume
* **Mileage:** The number of miles or kilometers that the vehicle can be driven.
* **Cylinders:** The number of cylinders in the vehicle's engine.
* **Gear box type:** It describes the type of transmission the vehicle has, such as "Automatic" or "Manual."
* **Drive wheels:** It indicates the type of drive wheels the vehicle
* **Doors:** It specifies the number of doors the vehicle has
* **Wheel:** It describes the type of wheels the vehicle has.
* **Color:** It represents the exterior color of the vehicle, indicating its visual appearance.
* **Airbags:** It specifies the number of airbags installed in the vehicle for safety purposes.
* **Yrs in Use:** It represents the number of years the vehicle has been in use or in ownership since its production year

### Objective
* **Data Exploration**: Explore the dataset to understand its structure, missing values, and basic statistics.
* **Data Cleaning**: Preprocess the data by handling missing values, outliers, and formatting issues.
* **Descriptive Analysis**: Conduct exploratory data analysis to uncover patterns and relationships in the data.
* **Visualizations**: Create visualizations (e.g., bar charts, histograms) to present findings effectively.

### Insights
* The dataset contains 19,237 rows and 18 columns representing used car listing details like make, model, year, mileage, price etc.
* Hyundai and Toyota are the top-selling models. The average Hyundai price is around $22k.
* Luxury brands like Lamborghini, Bentley, and Ferrari rank highest in average price, while mainstream brands like Hyundai, Toyota, and Ford rank much lower.
* The most expensive model listed is the Opel Combo at over $260k. The next highest models are in the $80k-$90k range.
* Petrol is by far the most common fuel type. Plug-in hybrid models have the highest median price, while CNG has the lowest.<p align="center"> <img src="https://github.com/Utkarsh11-git/EDA_Car_Price_Python-/assets/92782014/d193099a-7ee3-4f66-903c-0a8b292d9dac.png" width="600" height="300"> </p>
* Most cars listed are relatively new. They were introduced less than 20 years ago. Only a small percentage of listings are older. <p align="center"> <img src="https://github.com/Utkarsh11-git/EDA_Car_Price_Python-/assets/92782014/a6e9ae75-9c99-4023-b1cc-3c3e23186b33.png" width="600" height="400"> </p>
* There is very little correlation between price and levy amount, indicating levy is not a major factor in used car pricing.
* Cars with leather interiors tend to have a higher average price than those without, across different makes.
* Average used car price shows an overall increasing trend from the 1940s to the 2020s, with some drops and variability. Prices have surged since the 2010s.<p align="center"> <img src="https://github.com/Utkarsh11-git/EDA_Car_Price_Python-/assets/92782014/ff2a1315-8d0b-42c5-9ff7-4050f49db311.png" width="650" height="450"> </p>
* The linear regression model predicts a steep decline in the price in 2021 followed by a steady increase of over $1,000 every year

### Tools and Libraries
* **Python** programming language.
* Libraries such as **Pandas**, **NumPy**, **Matplotlib**, **Seaborn** and **Sklearn** for data manipulation and visualization.
* **Jupyter Notebook** in Visual Studio for documentation and analysis.

### Conclusion
This EDA project has provided a deeper understanding of vehicle pricing and the factors that influence it. The insights gained from this analysis can be leveraged for pricing strategies, market positioning, and decision-making in the automotive industry.
