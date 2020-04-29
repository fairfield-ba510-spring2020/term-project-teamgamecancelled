BA 0510 Final Project - Team Game Cancelled 
Michael Disanto, James Neri and Monika Sivilli

Overview: 
In this project, we created a normalized database for Fairfield University's Academic Calander and Course Catalogs. During our ETL process, we loaded data into a normalized database of our own design. We tested the domain, entity and relational integrity of our databases and demonstrated that all the course objectives were met. 

1) Design a normalized relational database that can contain all CSV data in your SourceData repository. Document the design with an ERD and a data dictionary.

[Course Data Dictionary](Docs/CourseDataDictionary.md)
[CourseDataERD](ERD_StarSchema/CoursedataERD.ipynb)

2) Create a SQLite database called CourseData.db in this folder. The database should exactly match your ERD. Populate the database with data from the CSV files.

[CourseDataETL](CourseDataETL.ipynb)

3) Design and build data warehouse called CourseDataWarehouse.db. Here we designed a Star Schema and tested 

[CourseDataWarehouse](CourseDataWarehouse.ipynb)


5)  Then we designed and populated a data warehouse to answer our analytics questions. Below is a list of our analytical questions:
    1. View of Fact Table
    2. Finance Department
    3. Where Is Biology Taught on Thursdays? 
    4. Who Taught in the Lecture Halls in Spring 2018? 
    5. When and Where was Accounting Taught in Spring 2019?