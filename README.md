# Data Integration and Analytic Processing - Eurovision Voting Trends Analysis  
**Institution**: Faculdade de Ciências da Universidade de Lisboa  
**Course**: Data Integration and Analytic Processing  
**Project Date**: 2022  
**Project Language**: Portuguese

## Project Overview
This group project involved the creation of a data warehouse and the analysis of trends based on a real-world topic of our choice. We selected the **Eurovision Song Contest voting trends** as a case study, exploring how this data could be used in online betting platforms. The project was divided into three parts, each building upon the previous one. The final goal was to create a robust data warehouse and use it to analyze various factors that might influence voting behavior.

### Table of Contents
- [Skills and Tools Used](#skills-and-tools-used)
- [Project Parts](#project-parts)
  - [Part 1: Data Collection and Cleaning](#part-1-data-collection-and-cleaning)
  - [Part 2: Data Warehouse Structure and Design](#part-2-data-warehouse-structure-and-design)
  - [Part 3: Data Analysis and Results](#part-3-data-analysis-and-results)
- [Key Results](#key-results)
- [Project Structure](#project-structure)

## Skills and Tools Used
- **Software**: Excel, PowerBI, Jupyter Notebooks (Python), PostgreSQL
- **Techniques**: Data collection and cleaning, data warehouse design, trend analysis, data visualization, querying using SQL
- **Applications**: Data warehouse design, Eurovision voting analysis, betting trend prediction

---

## Project Parts

### Part 1: Data Collection and Cleaning
In the first part of the project, we collected Eurovision voting datasets from open-access websites like Kaggle. The raw data was then cleaned and processed to ensure consistency, correctness, and readiness for analysis.

**Key Steps:**
- Data sourcing from Kaggle and other platforms
- Cleaning and preparing datasets
- Organizing data into a usable format

---

### Part 2: Data Warehouse Structure and Design
In the second part, we designed the structure of the data warehouse. Fact tables and dimension tables were created, establishing relationships between different dimensions, such as countries, performances, and voting results.

**Key Steps:**
- Creating fact tables for voting results
- Designing dimension tables (countries, performances, years)
- Building relationships between the tables

---

### Part 3: Data Analysis and Results
The third part of the project focused on analyzing the data warehouse. We posed several key questions related to Eurovision voting trends and used the warehouse to answer them. Some of the questions we explored include:
- Does the language of a song influence its result?
- Does the number of votes correlate with neighboring countries?
- Do current events affect voting patterns?
- How does the performance order impact the final result?

**Key Steps:**
- Querying the data warehouse using PostgreSQL
- Analyzing trends using PowerBI for visualization
- Writing Python scripts for deeper analysis

---

## Key Results

- **Influence of Language**: The analysis showed that songs performed in English generally received higher scores, indicating a possible language bias.
- **Neighboring Countries' Votes**: There was a significant correlation between neighboring countries and the number of votes exchanged, showing strong regional voting patterns.
- **Impact of Current Events**: No clear trend was found relating current events to voting behavior, though some anomalies were detected.
- **Performance Order**: Songs performed later in the show tended to receive higher votes, indicating a potential advantage related to performance order.

---
## Project Structure

The project is organized into the following folders:

- **Part1/**: Contains datasets and the first report focused on data collection and cleaning.
  - `Datasets/`: Raw Eurovision datasets.
  - `report_part1.pdf`: Report for Part 1 of the project.
  
- **Part2/**: Contains dimension datasets and the second report focused on the data warehouse structure.
  - `Dimensions/`: Dimension datasets.
  - `report_part2.pdf`: Report for Part 2 of the project.
  
- **Part3/**: Contains the final datasets, flat files, PowerBI files, SQL code, and Python scripts for data analysis.
  - `Datasets/`: Final version of the cleaned datasets.
  - `Flatfiles/`: Files used to feed the data warehouse.
  - `PowerBI, SQL and Images/`: PowerBI files, SQL code for data warehouse creation, and relevant images from the results.
  - `Python/`: Python scripts used for data analysis.
  
- **Presentation.pptx**: Final presentation for the project.
