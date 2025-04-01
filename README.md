# Fuel Consumption Forecasting Using Noon Reports

The repository contains my Bachelor's thesis (from 2021). The [summary](docs/Thesis_Summary.pdf) and the [anonymised thesis](docs/Anonymised_Thesis.pdf) can be found in the `/docs` directory. The code for the case study can be found in the [Jupyter notebook](Noon_Report_Analysis.ipynb).

This notebook offers a glimpse into the processes being conducted by data-driven shipping lines, in order to utilise the data from the **noon reports** (data sent by every vessel around noon, containing information revolving around weight, speed, location, and consumption).

The utilisation can be simple, like pure graph plotting. This might come after the data cleansing phase; necessary in noon reports, since they usually contain erroneous data, due to their nature of manual input.

Ultimately, the most advanced noon-report analytical applications utilise the data, in order to build statistical or machine learning models that predict fuel consumption.

## Features

- **Data Cleaning and Visualization:** Processes raw noon report data to correct errors and visualize key metrics.
- **Predictive Modeling:** Utilizes statistical and machine learning models to forecast fuel consumption (based on historical data).
- **Performance Evaluation:** Assesses the accuracy and reliability of the predictive models to ensure robustness.

## Data

Analysis is based on noon report data, which are sent- usually- every noon from the vessel to the shipping line. They contain data related to the time period they are related to, the vessels' route (location, speed), and some operating details, such as engine working hours, propeller total revolutions, and deadweight.


## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/nantoniou/Fuel-Consumption-Forecasting-Noon-Reports.git
   ```
   Navigate to the project directory:
   ```bash
   cd Fuel-Consumption-Forecasting-Noon-Reports
   ```

2. **Install Dependencies:**
   Ensure you have Python installed (preferably version 3.6 or higher). Install the required Python packages using:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook:**
   Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Open and execute the `Noon_Report_Analysis.ipynb` notebook to perform data analysis and build predictive models.

## Usage

This project is intended for data scientists, shipping analysts, and researchers interested in maritime data analytics and fuel consumption forecasting. By following the steps in the notebook, users can replicate the analysis, apply the models to their datasets, and extend the methodologies to suit specific needs.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to contributors and the open-source community for their invaluable support and resources.
