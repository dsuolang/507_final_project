# 507_final_project 

The goal of this 'find your dream home' project is to help people to make informed decision when they are trying to buy a home in the state of Michigan. The code is written in Jupyter Notebook, running ipynb file in Jupyter Notebook, Jupyther Lab is recommened. Required python packages are listed in the project documentation. This Jupyter notebook sections.

Section 1: Import required python packages
Section 2: Data source 1 Census API
Section 3: Data source 2 Zillow web scrapping
Section 4: Call data functions in section 2 and 3, and add additional hepler data crosswalk between zipcode and county
Section 5: Tree graph
Section 6: Interaction and visual presentation

Zillow function will scrap new data everytime we run the code, data cleaning and reformatting function aimed to be comperhensive but there might be small chance that it scrapped data that current function cannot process. If that happens, please run section 5 and 6, they will read the stored data. If everthing goes well, then stored data will be overwritten by newly scrapped data.

Interactive console offers the following options, users will be able type in a number between 1-8 to start, and then interact according to the prompt and instrcution.

Seaching:

1. See all home for sale listing in your city
2. Search home for sale by number of rooms
3. Search home for sale by squarefeet
4. Find an affordable home within your budget

Visualization:

5. Compare the average housing price across different cities in Michigan
6. Correlation between different aspects of home
7. Search for cities has top neighberhoods, highest median household income
8. Check housing price range for differnt floor plans
