# Junior Analytics Engineer Technical Test | E-Commerce Company

## Notice

This repository contains my solution for the technical test conducted during a selection process for a **Junior Analytics Engineer** position at an e-commerce company. Some parts of the original proposal text have been omitted or modified to maintain the confidentiality of the selection process.

## Test Proposal Summary (read the complete proposal [here](proposta_desafio_tecnico.md))

This is a practical challenge for the Junior Analytics Engineer selection process at an e-commerce company. The scenario involves planning for the beginning of the school year in São Paulo city, focusing on selling school supplies. The challenge aims to develop a simplified data preparation project to deliver a database that will be used in analyses and other projects during sales planning. The data should be made available in a structure and quality similar to the Silver layer of the Medallion Architecture. The data for the challenge includes aggregated student information and details about schools. Important: use only student profiles and school data from São Paulo city for the years 2021 and 2022.

## Steps of my Data Preparation Solution

1. Initial analysis of data quality and CSV file structures using Python + Pandas and Google Sheets.
2. Development of a [script](data_preparation/scripts/compare_delimited_file_headers) in Python to compare file headers (students and schools) with correct headers based on their respective data dictionaries.
3. Manual correction of identified issues using Google Sheets (correction of field names, changing column positions to correct positions, and deletion of completely empty columns or columns that don't exist in the data dictionaries).
4. Development of a [script](data_preparation/scripts/datasets_to_sqlite) in Python that applies some data preparation/cleaning steps necessary for the data to be correctly stored in the SQLite database.
5. Development of a [script](data_preparation/scripts/datasets_to_sqlite) in Python that creates the [SQLite database](sqlite_db) and performs data ingestion from files to the tables 'educandos' (data from student profiles enrolled in 2021 and 2022), 'escolas' (data about municipal schools for the years 2021 and 2022) and 'escolas_educandos' (table that joins the 'escolas' and 'educandos' tables).

## Analysis Suggestions

1. **Demographic Analysis**: Analyze student distribution based on demographic characteristics such as race, gender, and age. This can help the company better understand the diversity of their potential customers and develop products that meet the needs of different demographic groups.

2. **Special Educational Needs Analysis**: Analyze the distribution of students with special educational needs. This can help the company develop specific products for this segment, which can be an important consideration for many parents.

3. **Trend Analysis**: Compare data from 2021 and 2022 to identify trends. This can help the company predict future demand and prepare adequately to meet parents' needs.

4. **Cluster Analysis**: Group schools based on similar characteristics (such as location and size) and analyze sales trend differences between different groups. This can help the company better understand the specific needs of different school communities.

5. **Market Segmentation Analysis**: Identify market segments based on student and school characteristics. This can help the company customize its products and marketing strategies for different segments, allowing it to better meet parents' needs.
