# MLFinalProject

This GitHub repository contains the code and resources for the MLFinalProject. The project focuses on time series analysis and forecasting using various machine learning techniques. Below is an overview of the project structure and key components:

## Repository Structure

- **AllIndexes.py**: Python script to scrape the S&P information.
- **PreprocessRoundOne/DataPreprocessing.ipynb**: Jupyter notebook for preprocessing the data. It creates the `fullData.csv` file used with the LSTM model.
- **ARIMA_v4.ipynb**: Jupyter notebook containing an updated version of the ARIMA (AutoRegressive Integrated Moving Average) model.
- **VAR_v3.ipynb**: Jupyter notebook containing an updated version of the VAR (Vector Autoregression) model.
- **CS6140.pdf**: Report detailing the project, methodologies, results, and conclusions.

## Usage

1. **Data Scraping**: Run `AllIndexes.py` to scrape the S&P information and collect the necessary data.

2. **Data Preprocessing**: Preprocess the collected data using the Jupyter notebook `DataPreprocessing.ipynb` in the `PreprocessRoundOne` directory. This notebook prepares the data for further analysis and modeling.

3. **Time Series Analysis**:
   - Explore the updated ARIMA model in `ARIMA_v4.ipynb`.
   - Explore the updated VAR model in `VAR_v3.ipynb`.

4. **Report**: Refer to `CS6140.pdf` for a comprehensive report on the project, including methodologies, results, and conclusions.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes.
