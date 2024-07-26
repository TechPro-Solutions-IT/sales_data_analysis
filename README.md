# sales_data_analysis

This project aims to analyze the sales data from a kiosk selling candies, drinks, cigarettes, and other items. The analysis includes insights on popular products and categories, sales trends, and the impact of unit price on the quantity sold. The goal is to provide data-driven recommendations to optimize sales and improve overall store performance.

## Project Structure

- `data/`
  - `sales-06-07-24.csv`: The dataset containing sales records for analysis.
- `notebooks/`
  - `01_product_and_category_analysis.ipynb`: Jupyter notebook for analyzing product and category sales.
- `images/`
  - `lineal regression.png`: Image file of the linear regression analysis graph.
  - `total sales by product.png`: Image file of the total sales by product analysis graph.
  - `total sales by category.png`: Image file of the total sales by category analysis graph.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/techpro-solutions-it/sales_data_analysis.git
    cd sales_data_analysis
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Navigate to the `notebooks` directory:
    ```bash
    cd notebooks
    ```

2. Open the Jupyter notebook:
    ```bash
    jupyter notebook 01_product_and_category_analysis.ipynb
    ```

3. Run the cells in the notebook to execute the analysis and generate visualizations.


## Analysis Overview

### Descriptive Analysis of Products and Categories

The descriptive analysis helps identify the most and least popular products and categories. This information is crucial for inventory management and promotional planning.

### Linear Regression Analysis

The linear regression analysis aims to understand the impact of unit price on the quantity sold. The results suggest that there is no significant relationship between unit price and quantity sold, indicating that other factors might be more influential.

### Visualizations

The project includes various visualizations to help interpret the sales data, such as bar charts for product popularity and scatter plots for regression analysis.

## Conclusion

This project demonstrates the application of data analysis techniques to understand sales patterns in a kiosk. The insights gained from this analysis can guide strategic decisions to optimize sales and enhance store performance.

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, please reach out to:
- Email: [techpro.solutions.it@gmail.com](mailto:techpro.solutions.it@gmail.com)
