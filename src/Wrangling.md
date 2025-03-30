# Data Wrangling (Preprocessing)

## 1. Number of Deads Dataset

- **Actions Taken**:
  - Removed unnecessary columns (homicide type and total).
  - Null values were removed.
  - Column names were translated from Spanish to English (e.g., "asesinato" to "homicide").

## 2. National Urban, Poverty Dataset

- **Actions Taken**:
  - Retained only the columns for survey month, year, and KPI %.
  - Explanatory columns were removed.

## 3. Education Expenditure Dataset

- **Actions Taken**:
  - Removed indicator and code columns.
  - Years were pivoted into a single column.
  - Year format was changed to date.

## 4. Prisoners Dataset

- **Actions Taken**:
  - Data from 2024 and 2025 were combined using the **Union** function.
  - Removed irrelevant columns (civil status, gender, weapon type, etc.).
  - Retained only relevant columns: age, sex, nationality, education level, and detention date.
  - Column names were translated from Spanish to English.

## 5. Academic Registers Dataset

- **Actions Taken**:
  - Null values were cleaned.
  - Removed irrelevant columns (province, cities, canton type, etc.).
  - Retained only records of Ecuadorian students.
  - Column names were translated from Spanish to English.

To view these changes, please refer to the Tableau Prep flow file [Term Project Databases.tfl](Code/Term%20Project%20Databases.tfl).


---
[Home](README.md)

[Background](Background.md)

[Table of Contents](T.Contents.md)

