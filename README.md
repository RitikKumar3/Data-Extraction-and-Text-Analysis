# Data Extraction and Text Analysis 

## Instructions for Running the Python Script

### Dependencies

Make sure you have the following dependencies installed:
1.	Python Packages:
-	pandas
-	requests
-	beautifulsoup4
-	nltk
-	openpyxl (for Excel file handling)

  You can install these packages using pip:
- pip install pandas requests beautifulsoup4 nltk openpyxl

2.	NLTK Resources:

-	Download NLTK resources for tokenization and stopwords by running the following code once in Python:

-	import nltk
-	nltk.download('punkt')
-	nltk.download('stopwords')

### Setup

1.	Google Drive (if using Google Colab):

        Mount your Google Drive by running:

-	from google.colab import drive
        drive.mount('/content/drive')

2.	Directory Structure:

-	Ensure your project directory (Test Assignment) on Google Drive contains the following:

-	Input.xlsx: Excel file containing URLs and corresponding URL IDs.
-	Output Data Structure.xlsx: Excel file defining the structure of the output data.
-	TitleText directory: Directory to store text files extracted from URLs.
-	StopWords directory: Directory containing stopwords text files for NLTK.
-	MasterDictionary directory: Directory containing positive and negative sentiment word lists.

### Execution Steps

1.	Run the Script:
-	Open your preferred Python environment (e.g., Jupyter Notebook, Google Colab).
-	Copy and paste the Python script (text_analysis_script.py) provided earlier into a new Python script file.

2.	Execute the Script:
-	Run the script (text_analysis_script.py).
-	Ensure the script executes without errors. If any errors occur, check console output for details and adjust as necessary.

3.	Check Output:
-	After successful execution, the script will generate an Output_Data.csv file.
-	This file will be saved in the Test Assignment directory on your Google Drive.

#### Notes
-	Adjust paths ('/content/drive/MyDrive/Test Assignment/') in the script if your directory structure differs.
-	Ensure all dependencies are installed and resources are downloaded before running the script.
-	Verify the output CSV file (Output_Data.csv) matches the structure defined in Output Data Structure.xlsx.



### Acknowledgements
- The link for the dataset is :- https://drive.google.com/drive/folders/1iDlnco667tmszZwxb1FTHDXxmtyCM_4G?usp=sharing


### Contact
-Created by www.linkedin.com/in/ritik-kumar-717313221 - feel free to contact me!