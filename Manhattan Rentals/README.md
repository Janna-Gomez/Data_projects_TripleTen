# Manhattan Vacation Rentals #
 
 This was the second independent project for the Tripleten Business Intelligence Analyst program to analyze and report data. The project focused on skills from the Advanced Spreadsheet unit of the course.
An unnamed property rental agency requested recommendations on property investments.The company asked for an analysis of Airbnb data with insights inquired about which neighborhoods and property sizes are most attractive to travelers and how much money do the listings generate.
In the analysis of Airbnb rentals in Manhattan, based on the number of reviews from the past 12 months, it was found that the most popular properties are studios in Midtown and 1-bedroom units in the following neighborhoods: Harlem, Hell's Kitchen, Lower East Side, Upper West Side, Chelsea, East Village, East Harlem, West Village, and Upper East Side.

## Table of Contents ##
 
 | File # | Title | Description |
 | :-----------: | ----------- |----------- |
| 1 | [Manhattan Vacation Rental](https://github.com/Janna-Gomez/Data_projects_TripleTen/blob/main/Fresh%20Beats/Janna%20Gomez%20-%20Project%20Status%20Report.docx)| Data source provided by Tripleten used for analysis.|
| 2 | [README.md](https://github.com/Janna-Gomez/Data_projects_TripleTen/blob/main/Fresh%20Beats/Janna%20Gomez%20-%20Project%20Status%20Report.docx)| Current page provides information of project description. |
| 4 | [Rubric](https://github.com/Janna-Gomez/Data_projects_TripleTen/blob/main/Manhattan%20Rentals/Project_Rubric.pdf )|  File of rubric provided by course to complete the project successfully.|
| 5 | [Requirements](https://github.com/Janna-Gomez/Data_projects_TripleTen/blob/main/Manhattan%20Rentals/Requirements.txt)|  File of rubric provided by course to complete the project successfully.|

## README Table of Conents ##
 
 | Section Title | Description |
 | :-----------: | ----------- |
 | 1 | Description| The description of the project purpose, software, format, visuals.|
 | 2 | Process | Description of steps taken and tools used to complete steps. |
 | 3 | Assumptions | Provides information of assumptions from Tripleten and factors based on data. |
 | 3 | Findings & Recommendations | Provided insights and recommendations based on data analysis. |
 
#### Description:
- 11 spreadsheet
- Includes organizational tabs, raw data (Hidden), processed data, data analysis, pivot tables, and bar charts.

#### Process
**Data Preparation** Filtering techniquest used to identify and clean Airbnb dataset. Columns that were deemed irrelant were hidden.
**Functions used** PROPER, TRIM, IF, ISNUMBER, FIND, ROUND, SUMIF, VLOOKUP, CHOOSE, and WEEKDAY
**Neighborhood Analysis**: Identify the top-earing neighborhoods based on review frequency via *Pivot Table*.
**Property Size Analysis**: Determine the preferred property sizes for each neighborhoodvia *Pivot Table* showcased with *conditional formatting*.
**Revenue Analysis**: Calculate estimated annual revenue to identify the most attractive listings.
**Additional Optional Analysis**: Perform Analysis through *Pivot Tables* for occupancy rates by day, price by super host status, and price by review ratings.
**Data Visualization**: Create clear and informative *visualizations* (charts) to present findings.
**Formatting and Organization**: Ensure your analysis is well-formatted for ease of readability.
**Documentation**: Create organizational sheets like an executive summary, table of contents, assumptions log, and change log.

#### Data
The data was one Google spreadsheet file provided by TripleTen, A Copy can be found [here, click to open new tab](https://docs.google.com/spreadsheets/d/1_TVEAiVm6hfJvIV8HSkfxl1oKfPEtT7XinvkMGGKhiE/edit?usp=sharing):
- `'nyc_airbnb_data.csv'`: Each row corresponds to one listing on Airbnb in September 2022
    - `'data_dictionary'`: summary of field titles seen in the file and its data type
    - `'listings'`: unique listings available with all available data
    - `'calendar'`: listings with upcoming availabilities and date-type data

#### Assumptions
- Data is complete and accurate
- Nulls would not affect results

#### Findings & Recommendations

The "Attractive Neighborhoods/#_of_reviews" sheet includes a table and chart titled “Top 10 Neighborhoods by SUM of Reviews,” highlighting the neighborhoods with the highest review totals.

The top 10 neighborhoods with the most reviews in the past 12 months are: Midtown, Harlem, Hell’s Kitchen, Lower East Side, Upper West Side, Chelsea, East Village, East Harlem, West Village, and Upper East Side.

According to the "Property Size Popularity" sheet, 1-bedroom units and studios have received the most reviews, indicating that these property types are rented most frequently.

The "Neighborhood & Property Size" sheet ranks the top 10 neighborhoods by review count, showing that studios in Midtown have the highest number of reviews over the past 12 months. Additionally, all other top 10 neighborhoods show the highest review counts for 1-bedroom properties.

The total revenue generated by the properties in these neighborhoods amounts to $16,704,623.

Given these insights, it would be advantageous for Airbnb to focus its investments on studios in Midtown and 1-bedroom units in the neighborhoods identified above.

[<img src="https://github.com/Janna-Gomez/Data_projects_TripleTen/blob/main/Manhattan%20Rentals/Airbnb%20Top%2010%20Neighborhoods.png">]
[<img src="https://github.com/Janna-Gomez/Data_projects_TripleTen/blob/main/Manhattan%20Rentals/Property%20Size%20Popularity.png">]
