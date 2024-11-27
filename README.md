# School Supplies Market Data Preparation

Solution built for a Junior Analytics Engineer technical assessment. Read the complete challenge proposal [here](technical_challenge_proposal.md).

## 📊 About

Solution developed for a technical assessment that prepared educational data. The project processed data from:
- Student profiles (2021-2022)
- School information (2021-2022)
- São Paulo city only

## 🛠️ Technical Stack

- Python
- Pandas
- SQLite
- Google Sheets

## 🔄 Data Pipeline

1. **Quality Check**
   - Analyzed data quality in CSV files
   - Used Python, Pandas and Google Sheets

2. **Header Validation**
   - Developed a [Python script](data_preparation/scripts/compare_delimited_file_headers) to validate file headers
   - Compared against data dictionaries

3. **Manual Corrections**
   - Fixed field names
   - Adjusted column positions
   - Removed empty or invalid columns

4. **Data Preparation**
   - Created a [Python script](data_preparation/scripts/datasets_to_sqlite) for data cleaning
   - Prepared data for SQLite storage

5. **Database Creation**
   - Created [SQLite database](sqlite_db) with tables:
     - `educandos`: Student profiles (2021-2022)
     - `escolas`: Municipal schools data (2021-2022)
     - `escolas_educandos`: Relationship between schools and students

## 📈 Analysis Opportunities

The prepared database enabled various analyses for sales planning:

1. **Demographics**: Student distribution by race, gender, and age
   - Helped understand customer diversity
   - Guided product development

2. **Special Education**: Distribution of students with special needs
   - Identified opportunities for specialized products
   - Supported inclusive product planning

3. **Trends**: Year-over-year comparison (2021-2022)
   - Helped predict future demand
   - Guided inventory planning

4. **School Clusters**: Groups of schools by characteristics
   - Location-based analysis
   - Size-based segmentation

5. **Market Segments**: Identified distinct customer groups
   - Customized product strategies
   - Targeted marketing approaches

---

*Note: This project was developed as part of a technical assessment for a Junior Analytics Engineer position. Some details have been modified to maintain confidentiality.*
