# New-Zealand-Disability-Status
## Project objective:
Builing dashboards using MS Excel and Power Bi to analyse New Zealnd disability status by place of residence, age group, sex and ethnic group, 2006 Information on table.

## Tools:
- Data Cleaning: MS Excel
- Visualization: MS Excel
### 1	Question to answer
    1.1	What is the population of disabled and abled people by different age groups?
    1.2	What is the population of disabled and abled people by gender?
    1.3	What is the population of disabled and abled people by the type of residence?
    1.4	What is the population of disabled and abled people by ethnicity?
### 2	Data cleansing
    2.1	Downloading Disability Data from NZ.Stat tool on https://www.stats.govt.nz/
    2.2	Filtering unnecessary data from the “Dis. Status” column by:
        2.2.1	Keeping the “Population with disabilities “, and “Population without disabilities “and unchecked the “Population with and without disabilities”
        2.2.2	Filtering “total age group” data from the “Age group” column 
    2.3	Copying the cleared data into a new sheet called “Filtered Data” not miss the row data in case it might be needed
    2.4	Opening a new sheet as “Pivot Tables” to pivot tables from the “Filtered Data” sheet
        2.4.1	In the “Pivot Tables” sheet, 4 tables were generated:
            •	The 1st table looks at the number of disabilities per age group
            •	2nd table looks at the number of disabilities by gender
            •	3rd table looks at the number of disabilities by ethnicity
            •	4th table looks at the number of disabilities by the type of residences
        2.4.2	Generating a chart for each of these pivot tables next to the tables
### 3	Visualisation 
    3.1	Opening a new sheet to make the dashboard.
        3.1.1	Copying charts to the new sheet (“Dashboard” sheet)
        3.1.2	Adding four slicers for the different age groups, genders, types of residence and ethnicities from the “PivotChart Analyse” tab 
        3.1.3	Reporting the connections between the slicers and the Pivot Charts through “Report Connection” under the Slicer tab. 
