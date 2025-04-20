# AutoClean
AutoClean is an automated data cleaning tool built using Python. It helps clean datasets by performing various operations like handling missing values, outlier detection, data standardization, and normalization. This project is ideal for preprocessing and preparing datasets for further analysis or machine learning tasks.

Features
Data Preprocessing: Automatically handle missing values and detect outliers.

Data Standardization: Standardizes numerical data (mean = 0, standard deviation = 1).

Data Normalization: Scales numerical data to a specified range (e.g., [0, 1]).

Logging: Logs all operations performed on the data for traceability.

Folder Organization: Saves the cleaned data to a structured folder system (input, output, logs, src).

Installation
Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/AutoClean.git
Navigate into the project directory:

bash
Copy
Edit
cd AutoClean
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Alternatively, you can manually install dependencies:

bash
Copy
Edit
pip install pandas numpy scikit-learn
Usage
Step 1: Upload your dataset
Place your dataset in the input folder or upload it manually using the script.

The dataset should be in CSV format.

Step 2: Run the cleaning script
Run the Python script that performs the data cleaning:

bash
Copy
Edit
python autoclean_script.py
The script will process the dataset and save the cleaned data in the output folder.

Step 3: Check the logs
After the cleaning process is complete, the log file will be saved in the logs folder for tracking the operations performed.

File Structure
graphql
Copy
Edit
AutoClean/
│
├── input/                # Folder for input datasets
├── output/               # Folder for cleaned datasets
├── logs/                 # Folder for log files
├── src/                  # Folder for source code
│   └── autoclean_script.py  # Main script for cleaning the data
├── .gitignore            # Specifies which files should be ignored by Git
├── README.md             # Project documentation
└── requirements.txt      # Python dependencies
License
This project is licensed under the MIT License - see the LICENSE file for details.


