# Xetra ETFs ETL Pipeline

This project implements an Extract, Transform, Load (ETL) pipeline for processing and analyzing Exchange Traded Funds (ETFs) data from the Xetra trading platform. Developed using Python and pandas, it was created as part of a Udemy course on building ETL pipelines.

## 📁 Project Structure

- `xetra/`: Contains the core ETL logic and modules.
- `configs/`: Holds configuration files for the ETL process.
- `tests/`: Includes unit tests to ensure the reliability of the ETL components.
- `.vscode/`: Workspace settings for Visual Studio Code.
- `Pipfile` & `Pipfile.lock`: Manage project dependencies.

## ⚙️ Features

- **Data Extraction**: Fetches raw ETF trading data from the Xetra source.
- **Data Transformation**: Processes and cleans the extracted data for analysis.
- **Data Loading**: Stores the transformed data into a target destination for further use.
- **Modular Design**: Structured for scalability and ease of maintenance.
- **Testing Suite**: Ensures code quality and correctness through unit tests.

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- [Pipenv](https://pipenv.pypa.io/en/latest/) for managing virtual environments and dependencies

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mukhtar-dev/xetra_etl.git
   cd xetra_etl
   ```

2. **Install dependencies**:
   ```bash
   pipenv install
   ```

2. **Activate the virtual environmen**:
   ```bash
   pipenv shell
   ```

## 🛠️ Usage
To run the ETL pipeline:
   ```bash
   python xetra/main.py
   ```
Ensure that the configuration files in the configs/ directory are set up correctly to match your data sources and destinations.

## 🧪 Running Tests
To execute the tests:
   ```bash
   pytest tests/
   ```

## 📚 Acknowledgments
This project was developed as part of a Udemy course on building ETL pipelines with Python and pandas.
https://www.udemy.com/share/104SzU3@D3p9leiFyDG6nawBkYign1JVsDpdnIKPc0rbflWMlLikGakuCRes9fXM4NWDboit5Q==/

## 📄 License
This project is licensed under the MIT License.

