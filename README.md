# Outlier Detection Techniques

This Streamlit web application offers a comprehensive exploration of outlier detection techniques applied to a dataset containing age data. Below are the key features and functionalities of the application:

## Features:

1. **Dashboard**: The application includes a sidebar dashboard that provides easy access to different sections of the app.

2. **Normal Distribution & Z-scores**:
   - Visualizes the probability density function (PDF) of age data and highlights outliers using Z-scores.
   - Displays a box plot of age data and identifies outlier values.

3. **Isolation Forest**:
   - Applies the Isolation Forest algorithm to detect anomalies in the age data.
   - Visualizes outliers using scatter plots and box plots.

4. **Local Outlier Factor (LOF)**:
   - Utilizes the LOF algorithm to identify local outliers in the age data.
   - Presents outliers visually through scatter plots and box plots.

5. **Percentile-Based Method**:
   - Identifies outliers based on their position in a sorted list using top and bottom percentiles.
   - Displays top and bottom percentile outliers in separate tables.

6. **Winsorization**:
   - Implements Winsorization to transform the data by limiting extreme values (outliers) to a specified percentile.
   - Presents both original and winsorized age data in a single table.

## Libraries Used:

- Streamlit
- Pandas
- Plotly
- NumPy
- Scikit-learn

## How to Run:

To run the application locally, follow these steps:

1. Make sure you have Python installed on your system.
2. Install the required dependencies using pip:
3. Navigate to the directory containing `app.py` in your terminal.
4. Run the following command:
5. The application will open in your default web browser, allowing you to explore and experiment with different outlier detection techniques.

## Graphs Used:

- Probability Density Function (PDF) plot
- Box plot
- Scatter plot
- Table (for displaying outlier values)

## Contributions and Feedback:

Contributions to the project are welcome! If you encounter any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request on GitHub.

## Acknowledgments:

Special thanks to Streamlit for providing an intuitive framework for building interactive web applications with Python.


