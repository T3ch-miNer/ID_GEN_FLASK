## ID_GEN_FLASK

##Objective : Import your messy excel or CSV file and export it into a cleaned data where all the duplicate and fraudulent data(like name , number , address) is filtered.

HOW TO RUN :
after cloning this repo in your computer 
1. create database in [mysql](https://dev.mysql.com/doc/refman/8.0/en/windows-installation.html) server
   database name : flask_demo
   in this database import id.sql file.
2. open cmd
   python -m venv myvenv
   myvenv\Scripts\activate
   python app.py
3. go to http://127.0.0.1:5000/
   scroll down select task1
   load file only xlsx 
   row data file contain 'Name' and 'Mobile_Number' columns as header see demo.xlsx given in    folder.
4. Generate ID_Report File download in Excel format (ID_report.xls) download output file
   downloaded file in download folder by ID_report.xls name
