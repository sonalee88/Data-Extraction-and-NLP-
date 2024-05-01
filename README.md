This repository contains the code and instructions for the role position assessment for the company. The assessment involves extracting textual data articles from given URLs, performing text analysis, and computing various variables as specified in the assessment requirements.

Instructions
1. Approach to the Solution
Data Extraction:
Textual data articles are extracted from the provided URLs.
Python programming along with BeautifulSoup library is used for web scraping to extract the article text from each URL.
Website headers, footers, and any other irrelevant information are excluded while extracting the text.
Data Analysis:
After extracting the text, text analysis is performed to compute the required variables mentioned in the output data structure.
Python programming is used for text analysis, and variables such as sentiment scores, readability metrics, personal pronouns count, and syllables per word are calculated.
2. How to Run the Script
Ensure Python is installed on your system. If not, you can install Python from https://www.python.org/.
Clone or download this repository to your local machine.
Navigate to the directory containing the Python script (script.py) and input data files (input.xlsx, Text Analysis.docx, output structure.xlsx).
Install the required dependencies using pip:
Copy code
pip install -r requirements.txt
Run the Python script:
Copy code
python script.py
After the script has finished running, you will find the output data saved as an Excel file named output.xlsx in the same directory.
3. Dependencies
pandas
requests
beautifulsoup4
nltk
textblob
syllapy
You can install these dependencies using pip:

Copy code
pip install -r requirements.txt
If you encounter any issues or have questions, feel free to reach out for assistance.

Author
Sonali Kumari

License
This project is licensed under the MIT License.
