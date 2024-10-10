# Midterm Data Mining Project

This project applies association rule mining algorithms (Brute Force, Apriori, and FP-Growth) on supermarket transaction datasets. The goal is to generate association rules and compare the performance of different algorithms.

## Folder Structure
- This repsoistory contains the main Python script `source_code.py` and `source_code.ipynb` for generating association rules.
- **Datasets_CSV/**: Raw transaction datasets in CSV format.
- **Datasets_Binary_CSV/**: Binary-encoded datasets used by Apriori and FP-Growth algorithms.
- **DM_Binary_Datasets.xlsx**: Excel file containing binary-encoded datasets.
- **DM_Excel_Datasets.xlsx**: Original datasets in Excel format.
- **report.pdf**: The project report with detailed explanation.
- **requirements.txt**: Contains dependencies for the project (pandas and mlxtend).

## Setup Instructions
1. **Install Python (Version 3.6 or higher)**: Download and install from [python.org](https://www.python.org/downloads/).
2. **Install Required Libraries by Requirements File**: Run the following command to install the necessary packages:
    ```
    pip install -r requirements.txt
    ```
3. **Install Required Libraries by Manually**: Run the following command to install the necessary packages:
    ```
    pip install pandas mlxtend
    ```
4. **Running the Code**: Execute the Python file `source_code.py` by usuing command:
   ```
   python source_code.py
   ````
    or
   ```
   python3 source_code.py
   ````
   or open it in a Jupyter Notebook.

## Datasets
- The datasets are available in the `Datasets_CSV` and `Datasets_Binary_CSV` folders. These include supermarket transaction details for Amazon, Target, Costco, Walmart, and Aldi.
  
## Notes
- Ensure that dataset directory `Datasets_CSV` is in the same folder as the `source_code.py` and `source_code.ipynb` when running the code.
- For custom datasets user shoudl provide proper path of the CSV file.
- Errors in the output are marked with an asterisk (*) for easy identification.

## License
This project is open-source and available under the MIT License.
