# Practical Challenge | Data Preparation Project | Junior Analytics Engineer

Dear candidate,

Welcome to the practical challenge phase for the Junior Analytics Engineer selection process at our e-commerce company! In this challenge, you'll have the opportunity to apply your Analytics Engineer skills in a data preparation project scenario.

## Scenario

Imagine that our company is in full planning mode for the beginning of the school year in São Paulo city. Our focus is on selling school supplies. To ensure the success of this operation, we need well-prepared and structured data.

## Challenge Objective

Develop a simplified data preparation project where the final goal is to deliver a database that will be used in analyses and other projects by data analysts, business analysts, data scientists, and other stakeholders during sales planning. Your focus is to make the data available in a structure and quality similar to the Silver layer of the Medallion Architecture.

## Data for Use in the Challenge

### Aggregated Student Profiles

This data contains information about students, grouped by grade, shift, gender, age, special educational needs, and race/color. Each record in the student data represents a number of students per profile.

Access the student profile data [here](http://dados.prefeitura.sp.gov.br/dataset/perfil-dos-educandos-cor-raca-idade-sexo-necessidades-educacionais-especiais).

### School Information

This data provides details about schools, including location, school type, and other relevant information.

Access the school data [here](http://dados.prefeitura.sp.gov.br/dataset/cadastro-de-escolas-municipais-conveniadas-e-privadas).

#### *Important Notice*

Use only student profiles and school data from São Paulo city for the years 2021 and 2022. The selection of these specific years is due to the fact that the 2023 student data does not include the race field, an attribute we consider relevant for this type of project. Although we are currently in 2024, the scenario was designed to reflect the conditions and challenges that a company might face when planning its operations for the following year, based on available data from previous years.

## Instructions:

- Develop scripts or notebooks using Python and SQL (feel free to use the libraries of your choice).
- Make extensive use of comments in your code.
- Apply the KISS principle "Keep it simple, stupid!" in developing your project.
- Simplicity is a key element in the project. In our company, we prioritize simplified and effective processes, and this philosophy extends to our selection processes. Like you, candidates, we don't appreciate lengthy selection processes, especially for a junior-level position.
- In summary, our goal is to evaluate your current skills in: solving problems using SQL and the Python ecosystem, choosing which techniques and processes to apply in data preparation, planning, prioritizing and executing tasks, and organizing and documenting your work.
- We advise not to worry about using tools and libraries intended for data processing automation (such as ETL and orchestration). Additionally, we suggest not replicating the Medallion Architecture structure; we want you to just use the Silver layer concept as inspiration.
- Use a SQLite database as the final repository for the project data.
