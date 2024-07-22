# Emission-Explorer

## Description

The goal of Emission Explorer is to assist stakeholders in decision-making for continuous improvement by providing insights into renewable energy usage and its geographical distribution. By analyzing the eGRID dataset and API from www.eia.gov, the project aims to:

- Provide visualizations and analytical tools for stakeholders.
- Identify areas with the least renewable energy usage.
- Forecast future statistics related to renewable energy.

This Project uses the following tools

- **Data from www.eia.gov API**: Information from the www.eia.gov website was pulled using Python to enrich the analysis and provide comprehensive insights.
- **Tableau**: Utilized for visualization of the datasets, allowing stakeholders to explore data interactively and gain insights visually.
- **ARIMA Modeling in Python**: Employed for time series analysis and forecasting future statistics related to renewable energy usage.
- **ARMIA Charts in D3**: Used D3 to show visualizations of the forecasts of ARIMA models
- **EKC Charts in Python**: Used to explore the Environmental Kuznets Curve and analyze the relationship between environmental quality and economic development.
- **Correlation Analysis in Python**: Conducted to identify correlations between different variables in the dataset and understand their impact on renewable energy usage.

## Installation

To get started with Emission Explorer, follow these steps:

**Download the Project Files**: Download the project files zip file
   
2. **Extract the Zip File**: Extract the contents of the zip file to your local machine.

3. **Explore the Notebooks**: Open the extracted folder and explore the provided Jupyter Notebook (.ipynb) files to understand the analysis and visualization process.

To use Emission Explorer for your own analysis, follow these guidelines:

1. **Prepare Data**: Obtain the eGRID dataset, data from EIA.gov, or similar datasets relevant to renewable energy usage in geographical areas.
  a. Create your own free API key at eia.gov/opendata
3. **Data Preprocessing**: Preprocess the data as necessary, including cleaning, formatting, and handling missing values.
4. **Analysis**: Use the provided notebooks as a reference to conduct your analysis, including time series analysis, correlation analysis, and visualization.
5. **Visualization**: Utilize Tableau, D3 and other visualization libraries in Python to visualize the results and gain insights.
6. **Decision-making**: Use the insights gained from the analysis to make informed decisions regarding renewable energy policies and initiatives.

## Execution
For Tableaau Vizualization, visit: https://public.tableau.com/app/profile/shweta.saxena4326/viz/EmissionExplorer_Dashboard/Dashboard1?publish=yes
The filters can be changed to view different years, resource types and sectors

To run a demo of the code, follow these steps:

1. **Install Jupyter Notebook**: If you haven't already, install Jupyter Notebook by following the instructions [here](https://jupyter.org/install).

2. **Open Jupyter Notebook**: Navigate to the directory where you extracted the project files and open a terminal or command prompt. Then, run the following command:

   ```bash
   jupyter notebook

For the D3 Visualization of the ARIMA do the following:
1. Open a terminal or command prompt.
2. Navigate to the directory where the Emission Explorer D3 folder is located. You can use the cd command to change directories.
3. Once you're in the correct directory, use this command: python -m http.server 8000
4. After running the command, Python will start a simple HTTP server on port 8000 (you can choose a different port if you prefer). You'll see output in the terminal indicating that the server is running.
5. Open a web browser and navigate to http://localhost:8000 to access the files served by the local server. Replace 8000 with the port number you chose if you used a different one.
   
## Contributors
- Sharvari Mhatre
- Shweta Saxena
- Alicia Taylor
- Namra Ghafoor