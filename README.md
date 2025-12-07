# Analysis of OSHA Injury Application Data - 01/2024 - 12-2024

This dataset contains data from OSHA on workplace injury and illness data throughout the year.

# Data
This analysis uses one spreadsheet. You can find it here: https://www.osha.gov/Establishment-Specific-Injury-and-Illness-Data.
Each of the spreadsheets contains the following columns relevant to the analysis:
- id: Unique identifier for each entry
- company_name: Name of the business/company
- sector: The type of industry sector the company/business was in
- annual_average_employees: Average amount of employees working at the business/company each year
- total_hours_worked: The amount of hours worked by all of the employees that year
- total_injuries: Total amount of injures reported
- total_skin_disorders: Total amount of skin disorders reported
- total_respiratory_conditions: Total amount of respiratory conditions reported
- total_poisonings: Total amount of poisonings reported
- total_hearing_loss: Total amount of hearing loss incidents reported
- total_other_illnesses: Total amount of other illnesses reported

# Methodology
The notebook disney.ipynb performs the following analyses:

Part 1: Remove all entries with an average employee amount of 0

Part 2: Sum up all of the injury and illness columns into one column

Part 3: Sort the dataframe by total injuries in descending order

Part 4: Isolate all of the Disney entries and remove the companies that are not Disney related or a contractor of Disney

Part 5: Calculate the injury rates for Disney and compare it to average industry rates

# Outputs
The notebooks output this spreadsheet which contains: output/all_death_sector_summ.csv & output/all_inj_sector_summ.csv & output/disney.csv

# Running the Analysis Yourself
You can run the analysis yourself. To do so, you'll need the following installed on your computer:
- Python 3
- Pandas

# Licensing
All code in this repository is available under the MIT License. All files in the data/ directory are released into the public domain.

# Feedback/Questions?
Contact Shenal Tissera at tisserashenal@gmail.com
