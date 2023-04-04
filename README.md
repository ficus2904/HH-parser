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

1. Clone/Download the repository git clone https://github.com/yourusername/your-project.git
2. After cloning the repository, navigate to the project directory and install the required dependencies using the following command:
```pip install -r requirements.txt```
3. Once the installation is complete, you can run the project using the following command:
```python app.py```
4. After successfully running the script, an Excel workbook will be saved in the `files` folder. Each sheet of workbook containing details on all vacancies fetched from API

### Notes:
 - Python 3.8+ required to deal with asynchronous functions
 - If the `./files` directory does not exist, it will be created automatically 
 - Vacancies with the following words in their name or requirement will be removed: 'iddle', 'имлид', 'enior'.
 - You can change the query parameters in the params variable