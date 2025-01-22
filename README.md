<h1>🏠Predicting House Prices in King County</h1>

Welcome to the Predicting House Prices in King County repository! This project showcases a comprehensive data science workflow for predicting house prices using real-world data from King County, Washington.

<h3>📊 Project Overview:</h3> 

Housing prices are influenced by a myriad of factors, from square footage to location. This notebook dives deep into analyzing and predicting house prices using **machine learning techniques.** It's a perfect demonstration of how to combine exploratory **data analysis, feature engineering,** and **predictive modeling into a cohesive pipeline**.

<h3>🎯Objectives:</h3>

* Understand key factors driving housing prices.
* Build predictive models to estimate house prices accurately.
* Provide insights for real estate investors, homeowners, and industry professionals.

<h3>Data Used</h3>

-------------------------------------------------------------------------------------
| Variable      | Description                                   | Used in the Model  |
|---------------|-----------------------------------------------|--------------------|           
| Price         | Prices of the houses (Target Variable)        |        Y
| Bedrooms      | Number of bedrooms                            |        Y
| Bathrooms     | Number of bathrooms                           |        Y
| Floors        | Number of floors                              |        Y    
| sqft_livin    | Square footage of the home                    |        Y
| sqft_lot      | Square footage of the lot                     |        Y
| floors        | Total floors (levels) in house                |        Y  
| waterfront    | House with a view to a waterfront             |        Y
| view          | Has been viewed                               |        N
| condition     | Overall condition of the house                |        Y
| grade         | Overall grade given to the housing unit       |        Y  
| sqft_above    | Square footage of house apart from basement   |        N
| sqft_bmnt     | Square footage of the basement                |        Y
| yr_built      | Built year                                    |        Y
| yr_renov      | Year when house was renovated                 |        Y
| zipcode       | Zip code                                      |        Y
| lat           | Latitude coordinate                           |        N
| long          | Longitude coordinate                          |        N
| sqft_l15      | Living room area in 2015 (some renovations)   |        Y
| sqft_lt15     | Lot size area in 2015 (some renovations)      |        Y

<h3>🛠️ Tools and Technologies</h3>

  * Programming: Python
  * Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
  * Environment: Jupyter Notebook

<h3>Result</h3>
In the test dataset, 70% of the predictions for home prices can be explained by my model.The model predicts the home prices in King Couty with an error of +-1.3% of the actual prices.As I focussed only on the physical features of the house,I can conclude that house prices are not only based on the physical properties of a house but also on several other factors.

<h3>Future Enhancements</h3>

  * Add more advanced models like Gradient Boosting or Neural Networks.
  * Incorporate external data (e.g., interest rates, economic indicators).
  * Deploy the model as a web app using Flask or Streamlit.


