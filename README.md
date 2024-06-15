# Food Allergen Analysis README

## About:

Welcome to the Food Allergen Analysis project! This project focuses on analyzing a dataset that covers a wide range of allergens commonly found in food items. The dataset includes information about allergens in various food products, which can help in understanding the presence and absence of specific allergens in different food items.

The dataset includes several fields that provide valuable information about the products. Here are the key fields available in the dataset:

- **Food Product**: The name of the food product.
- **Main Ingredient**: The primary ingredient in the food product.
- **Sweetener**: The type of sweetener used, if any.
- **Fat/Oil**: The type of fat or oil used, if any.
- **Seasoning**: The type of seasoning used, if any.
- **Allergens**: A list of allergens present in the food product.
- **Price ($)**: The price of the food product in dollars.
- **Customer rating (Out of 5)**: The customer rating for the food product.
- **Prediction**: Indicates whether the product contains allergens or not.

### Sample Dataset:
| Food Product        | Main Ingredient | Sweetener | Fat/Oil       | Seasoning       | Allergens              | Price ($) | Customer rating (Out of 5) | Prediction |
|---------------------|-----------------|-----------|---------------|-----------------|------------------------|-----------|-----------------------------|------------|
| Almond Cookies      | Almonds         | Sugar     | Butter        | Flour           | Almonds, Wheat, Dairy  | 10.15     | 3.1                         | Contains   |
| Almond Cookies      | Almonds         | Sugar     | Butter        | Flour           | Almonds, Wheat, Dairy  | 6.17      | 4.5                         | Contains   |
| Chicken Noodle Soup | Chicken broth   | None      | None          | Salt            | Chicken, Wheat, Celery | 19.65     | 4.1                         | Contains   |
| Chicken Noodle Soup | Chicken broth   | None      | None          | Salt            | Chicken, Wheat, Celery | 17.48     | 4.7                         | Contains   |
| Cheddar Cheese      | Cheese          | None      | None          | Salt            | Dairy                  | 10.83     | 3.7                         | Contains   |
| Ranch Dressing      | Buttermilk      | Sugar     | Vegetable oil | Garlic, herbs   | Dairy                  | 9.92      | 2.3                         | Contains   |
| Caramel Popcorn     | Popcorn         | Sugar     | Butter        | Salt            | Dairy                  | 6.14      | 3.2                         | Contains   |
| Caesar Salad        | Romaine lettuce | None      | Olive oil     | Parmesan cheese | Dairy                  | 14.99     | 4.8                         | Contains   |

## Work Done:

### Data Cleaning:
- Checked for unique values in the dataset.
- Performed exploratory data analysis (EDA), including descriptive statistics and checking for null values using `isnull`.
- Replaced null values with 'None' to clean the dataset.

### Data Analysis:
- Generated a correlation matrix and visualized it with a correlation graph.
- Created histograms and boxplots for numerical columns to understand their distributions.

### Data Modeling:
- Split the dataset into training and testing sets.
- Applied various machine learning models including Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Gaussian Naive Bayes.
- Used Term Frequency-Inverse Document Frequency (TF-IDF) for feature extraction.
- Evaluated the accuracies of these models to determine their performance.

## Repository Structure:
- **data**: Contains the raw dataset and any processed data files.
- **notebooks**: Jupyter notebooks used for data cleaning, EDA, modeling, and analysis.
- **results**: Results and outputs generated from the analysis, including visualizations and reports.

## Getting Started:
1. Clone this repository to your local machine.
2. Ensure you have Python 3.x installed along with necessary libraries (e.g., pandas, numpy, matplotlib, seaborn, scikit-learn).
3. Navigate to the `notebooks` directory and open the Jupyter notebooks to explore the analysis and results.
4. Follow along with the steps outlined in the notebooks to reproduce the analysis or modify it as needed.

## Contributing:
- Contributions to this project are welcome! Feel free to fork this repository, make changes, and submit pull requests.
- For major changes, please open an issue first to discuss proposed updates or improvements.

## Contact:
For any questions, suggestions, or issues, please feel free to contact me via email at [your_email@example.com].

Thank you for your interest in the Food Allergen Analysis project! I hope you find the insights generated from the analysis valuable.
