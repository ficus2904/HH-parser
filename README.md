# Python Vacancies in HeadHunter

This script allows you to get information about Python related vacancies from HeadHunter through their API. After getting the data, preprocess and clean variables in it and convert it to an Excel file. 

### Libraries Used:
 - aiohttp
 - asyncio
 - re
 - os
 - requests
 - math
 - openpyxl
 - pandas
 - datetime
 - benedict

### How to Use:

1. Clone/Download the repository git clone https://github.com/ficus2904/HH-parser.git
2. Change into the project directory: ```cd your-repo``` and then create a virtual environment:```python -m venv env```
3. Activate the virtual environment:
```source env/bin/activate``` On Linux or macOS
```env\Scripts\activate.bat```  On Windows
4. Install the required dependencies using the following command:
```pip install -r requirements.txt```
5. Once the installation is complete, you can run the project using the following command:
```python app.py```
6. After successfully running the script, an Excel workbook will be saved in the `files` folder. Each sheet of workbook containing details on all vacancies fetched from API

### Notes:
 - Python 3.8+ required to deal with asynchronous functions
 - If the `./files` directory does not exist, it will be created automatically 
 - Vacancies with the following words in their name or requirement will be removed: 'iddle', 'имлид', 'enior'.
 - You can change the query parameters in the params variable