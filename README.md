# Medicare Fraud Detection

This project aims to detect potential fraud in Medicare Part D (prescription drug coverage) claims using machine learning techniques. The project analyzes Medicare Part D prescriber data, payment data, and exclusion data from the List of Excluded Individuals and Entities (LEIE) to identify patterns and anomalies that may indicate fraudulent behavior.

## Data Sources

The project utilizes the following data sources:

1. **Medicare Part D Prescriber Data**: This dataset contains information about prescriptions written by healthcare providers, including the National Provider Identifier (NPI), drug name, total drug cost, claim count, and day supply.

2. **Open Payments Data**: This dataset includes payment information made by pharmaceutical companies to healthcare providers, such as physicians and teaching hospitals.

3. **List of Excluded Individuals and Entities (LEIE)**: This dataset contains information on individuals and entities that have been excluded from participating in federal healthcare programs due to various reasons, including fraud and abuse.

## Features

The project includes the following features:

- Data preprocessing and cleaning
- Feature engineering
- Exploratory data analysis
- Machine learning model training and evaluation
- Fraud detection and scoring

## Usage

To run the project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/medicare-fraud-detection.git`
2. Navigate to the project directory: `cd medicare-fraud-detection`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Download the necessary data files and place them in the appropriate directories.
5. Run the main script: `python main.py`

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

This project was inspired by the Medicare Fraud Detection project and the data sources used are publicly available from the Centers for Medicare & Medicaid Services (CMS) and the Department of Health and Human Services (HHS).
