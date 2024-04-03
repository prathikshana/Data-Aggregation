# Data-Aggregation
The Auto dataset analysis is available in this repository. The dataset offers details on a number of automobile attributes.

# Getting Started

## Prerequisites
Python 3.x
Pandas library

## Installation
Clone the repository to your local machine:
git clone  > https://github.com/your-username/your-project.git
Navigate to the project directory:
cd your-project
Install the required dependencies:
pip install -r requirements.txt

## Usage

To use the project, follow these steps:

1. Open the terminal and navigate to the project directory.

2. Run the following command to start the application:
python main.py

3. Open a web browser and go to http://localhost:8000 to access the application.
   
## Contents
Auto.csv: CSV file containing the automotive dataset.
data_aggregation.ipynb: Jupyter Notebook containing the Python code for data aggregation and summarization.

## Dataset Overview

The Auto dataset consists of the following columns:

- `symboling`: Insurance risk rating
- `normalized-losses`: Normalized losses
- `make`: Manufacturer's brand name
- `fuel-type`: Type of fuel
- `aspiration`: Type of aspiration (turbo or standard)
- `num-of-doors`: Number of doors
- `body-style`: Body style (e.g., sedan, convertible)
- `drive-wheels`: Drive wheels (front, rear, or four-wheel drive)
- `engine-location`: Location of the engine (front or rear)
- `wheel-base`: Wheelbase
- `length`: Length
- `width`: Width
- `height`: Height
- `curb-weight`: Curb weight
- `engine-type`: Type of engine
- `num-of-cylinders`: Number of cylinders
- `engine-size`: Engine size
- `fuel-system`: Fuel system
- `bore`: Diameter of the engine cylinders
- `stroke`: Length of the piston stroke
- `compression-ratio`: Compression ratio
- `horsepower`: Horsepower
- `peak-rpm`: Peak RPM
- `city-mpg`: Miles per gallon (city)
- `highway-mpg`: Miles per gallon (highway)
- `price`: Price

## Contents
Auto.csv: CSV file containing the automotive dataset.
data_aggregation.ipynb: Jupyter Notebook containing the Python code for data aggregation and summarization.

## Summary of Analysis
The Python code reads the CSV file into a pandas DataFrame.
It performs data type conversion, checks for null values, and aggregates the data using various pandas functions.
Histograms are generated to visualize the distribution of numerical variables.

# Deployment
Make sure you have installed the relevant libraries and have set up the proper Python environment before deploying this data summarizing method. After that, you may utilize this script in your environment or project by doing the following:

1. Verify that Python is installed.
2. Use pip install pandas to install the necessary libraries (pandas) if they are not already installed.
3. Make sure the CSV file (Auto.csv) is located in the same directory as your script, or use the pd.read_csv() method to supply the right path to the file.
4. The given code should be copied and pasted into your Jupyter Notebook or Python script.
5. Launch the notebook or script.
This will read the CSV file, fix the data types, compile the information, and use histograms to display it.

## Tests
Ensure the dataframe is loaded correctly.
Check if the data types are converted as expected.
Verify the first few rows of the dataframe.

## Contributing
Contributions are welcome! Please make a pull request if you discover any problems or would like to add additional functionality.

## Authors
 - Omar Al-Trad

## Acknowledgement
In this project, the Python libraries listed below were utilized:

• [Pandas](https://pandas.pydata.org/): An effective library for data analysis and manipulation.
