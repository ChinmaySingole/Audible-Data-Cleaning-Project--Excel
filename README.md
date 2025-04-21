
# Audible Data Cleaning

## Problem Statement
To clean and standardize raw Audible audiobook data using Microsoft Excel's Power Query Editor. The aim is to prepare a structured and analysis-ready dataset by resolving inconsistencies in text, time, date, and numeric formats.
This project reflects the first phase in a data analytics pipeline: transforming messy, unstructured data into a reliable foundation for further analysis, visualization, or modeling.

## Cleaning Objectives

-  Standardize `name` to Title Case  
-  Split `author` into `First Name` and `Last Name`  
-  Format `releasedate` to `DD-MM-YYYY`  
-  Convert `time` to Excel-recognized `hh:mm:ss` duration  
-  Format `price` as numeric, identify invalid entries (e.g., “Free”)  
-  Convert `stars` from text ("4.5 stars") to numeric (`4.5`)  
-  Split multiple narrators in `narratedby` into separate columns  
-  Create `releaseinfo` column → `"DD-MM-YYYY, Language"`  
-  Ensure consistent 2-decimal currency format in `price`  

## Tools & Techniques
- Power Query Editor (Excel) – Used for efficient data cleaning and transformation

- Data Type Standardization – Ensured consistent formatting across date, numeric, and text fields.
- Custom Column Formulas – Applied logic to extract or compute values like duration in hours or combined fields.
- Text and String Functions – Cleaned and formatted columns such as name, author, stars, and price.
- Splitting and Merging Columns – Broke down combined values (like narrators or author names) and merged fields for enriched context (e.g., releaseinfo).


##  Future Improvements

-  Automate the cleaning using Python and Pandas
-  Build an interactive dashboard in Excel using the cleaned data
-  Perform statistical analysis on audiobook trends and pricing
-  Add genre or review sentiment analysis for richer insights

## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.


