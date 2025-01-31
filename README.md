# real_estate_socioeconomic_analysis
real_estate_socioeconomic_analysis
Real Estate Socioeconomic Analysis
This project analyzes factors influencing real estate prices across Canadian regions. It identifies patterns and explores correlations between property features (e.g., bedrooms, bathrooms) and socioeconomic factors (e.g., population size, income), examining how these elements impact housing affordability and price variations.

Getting Started
Installation
Make sure you have the following software installed:

Python 3.7+: The programming language used for this project
pip: Python package installer (usually included with Python)
Anaconda: Download conda 22.9.0 or later
Jupyter Notebook: For running and exploring the notebooks
Create a virtual environment conda create -n realestate_venv python=3.10 anaconda -y

Activate the realestate_venv virtual environment conda activate realestate_venv

Install the necessary dependencies listed in requirements.txt. These include:

pandas
pathlib
matplotlib
scipy
seabron
numpy
Install the dependencies in requirements.txt: pip install -r requirements.txt

Clone the repository: git clone https://github.com/anjgh/real_estate_socioeconomic_analysis.git cd real_estate_socioeconomic_analysis

Usage
This program can be used both in Windows and macOS using VS code.

Launch Jupyter Notebook of choice:

Each team member has a folder with the corresponding Jupyter Notebook with its detailed steps for analyzing different aspects of the dataset. You can run the cells to see the intermediate steps and results.
Data Files population_analysis.ipynb: Notebook analyzing the relationship between population and housing affordability. income.ipynb: Notebook analyzing the relationship between median family income and housing prices. geo_analysis.ipynb: Analyzing correlation pf geographical location and housing prices in Canada. ageeducation.ipynb: Researching how age and education level impact homeownership in two of the most expensive and least expensive cities in Canada.

Development
git clone https://github.com/anjgh/real_estate_socioeconomic_analysis.git cd real_estate_socioeconomic_analysis conda create -n realestate_venv python=3.10 anaconda -y conda activate realestate_venv pip install -r requirement.txt jupyter notebook

If contributing, clone the repo and create a new branch for your changes: git checkout -b feature/your-feature After making your changes, submit a pull request for review.

Introduction to Real Estate Socioeconomic Analysis
The project aims to analyze the factors that affect real estate prices in different regions, identify key patterns, and explore correlations between property features (e.g., number of beds and baths) and socioeconomic factors. The main question we started with is, how do socioeconomic factors such as population size, median family income, age, education, and geographical location influence real estate prices across various cities and provinces? Each team member researched each category of factor that may be affecting real estate prices in Canadian cities. We all made visualizations to show our results.

How does housing affordability vary across different Canadian cities? Is there a correlation between city population size and average house price? How does population density (people per square kilometer) influence housing prices and affordability across Canadian cities?
How does median family income influence housing prices across Canadian cities? Which cities have the greatest disparity between median family income and average housing prices? What is the distribution of house prices within a highest/lowest disparity city?
Is there a correlation between the density of population and bedrooms/bathrooms in homes across Canadian cities? Which cities have the highest average price per bedroom? What is the relationship between the number of bedrooms and home ownership in urban versus rural areas? How do housing prices vary between areas with high population (urban) versus lower population (rural) areas?
How does age and education level affect home ownership in the most expensive city versus the least expensive city in Canada?
Answering Research Questions
Housing affordability was calculated using a price-to-income ratio using two data frames. A correlation between city population size and average house price was found through a scatter plot. Population density data from the dataset was used to compare the housing affordability ratio. The goal was to determine if higher population densities are associated with higher house prices and lower affordability.

There is a positive relationship between income and house prices based on the slope of the line, the weak R-squared value and the borderline p-value suggest that income alone is not a strong or significant factor in predicting house prices in this data set. Other factors may be influencing house prices more strongly. Two bar graphs were made with the 10 cities with the highest disparities and the lowest disparities. Vancouver is the most expensive city in Canada with the highest disparity in income and Edmonton is the most affordable city in Canada with a disparity ratio of 4. A histogram was made for both Vancouver and Edmonton to see the distribution in the number of houses per price range. Edmonton has a left-skewed distribution and Vancouver has many more luxury homes with less affordable housing.

To explore the effect of population density and income on housing prices, we calculated correlation coefficients and created scatterplots:

Correlation between population density and housing price: We found a weak positive correlation (0.11), indicating that areas with higher population density have slightly higher housing prices.
Correlation between median income and housing price: This was also weak (0.05), suggesting that income alone does not strongly predict housing prices. The conclusion was that while population density and income do affect housing prices, other factors (e.g., geographic location, and housing demand) likely play a larger role in determining prices. We compared housing prices between urban and rural areas by creating a box plot and calculating correlation values. This showed:
Urban areas have higher median housing prices than rural areas, and the range of prices is wider in urban settings, indicating more variability (from affordable to luxury homes).
Rural areas have lower prices and a smaller range, suggesting more uniform, affordable housing. Overall, the analysis showed clear trends in the Canadian housing market: urban areas are more expensive, and although population density and income have some impact on housing prices, they are not the sole determining factors. The top cities with the highest price per bedroom reflect the broader trend of urbanization driving up housing costs.
In Edmonton, homeownership is highest among 35 to 44-year-olds. This may indicate that Vancouver has homeowners who are older while Edmonton has younger homeowners. In general, 3 age groups between 35 to 64 seem to have the highest rate of homeownership. For both cities, home ownership seems to be highest among people who have a Bachelor's degree. The gap between homeownership between a Bachelor's degree and a High School Diploma for Edmonton and Vancouver is less than 50000. Edmonton has a smaller gap in Education level compared to Vancouver
