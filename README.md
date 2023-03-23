# Поиск информации о банкротстве
Этот репозиторий содержит Python-скрипт для поиска информации о банкротстве на основе ИНН клиентов с сайта "Коммерсантъ" и соответствующего обновления файла данных клиентов в Excel.

## **Usage**

### **Test the Code**

To test the code, use sections 1 and 5.

### **Section 2**

Section 2 is provided to demonstrate the use of an existing company script for extracting INN information for clients.

### **Section 3**

Section 3 is provided to demonstrate the expected parsing from the Kommersant website. However, due to the presence of CAPTCHA, the code cannot be fully tested and run as intended. You may need to implement an alternative solution for bypassing CAPTCHA, such as using third-party libraries or services.

## **Prerequisites**

- Python 3.6 or later
- pandas
- openpyxl
- PyPDF2

## **Installation**

1. Clone the repository or download the source code.

```
bashCopy code
git clone https://github.com/yourusername/bankruptcy_information_search.git

```

1. Change the working directory to the project directory.

```
bashCopy code
cd bankruptcy_information_search

```

1. Install the required packages using pip.

```
Copy code
pip install -r requirements.txt

```

1. Run the Python script.

```
Copy code
python bankruptcy_search.py

``` 
