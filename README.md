# Data-cleaning

## 📅 Task Completed: Data Cleaning

*Date:* 2025-05-26
*Objective:* Clean and prepare dataset by following standard data preprocessing steps.

### 🧹 Steps Completed:

#### 1. *Handled Missing Values*

* Used *Excel filters* to identify missing cells ((Blanks)).
* Filled or removed missing values depending on context.
* Example: Missing gender entries were replaced with "Unknown".

#### 2. *Removed Duplicate Rows*

* Applied *Data > Remove Duplicates* in Excel.
* Verified the uniqueness of key identifiers before deletion.
* Ensured no critical records were accidentally removed.

#### 3. *Standardized Text Values*

* Used *Find & Replace (Ctrl + H)* to correct inconsistent labels (e.g., "MALE", "male", "Male" → "Male").
* Applied the following Excel text functions:

  * =LOWER(), =UPPER(), and =PROPER() to normalize case.
* Standardized entries in columns like *Gender, **Country*, etc.

#### 4. *Converted Date Formats*

* Reformatted all dates to *dd-mm-yyyy* using:

  * *Right-click > Format Cells > Date*
  * Where needed, used =DATEVALUE() to convert text to real dates.
* Ensured consistency across all date fields.

#### 5. *Renamed Column Headers*

* Updated all column headers to:

  * Use *lowercase letters*
  * Remove *spaces and special characters*
  * Example: "First Name" → first_name, "Date of Birth" → dob
* This helps in better compatibility with code and databases.

#### 6. *Checked & Fixed Data Types*

* Identified numbers and dates stored as *text*.
* Converted text to proper types using:

  * =VALUE(A2) for numeric fields (e.g., age, income)
  * =DATEVALUE(A2) for date fields
* Ensured that:

  * *Age* is stored as integer
  * *Date* is stored as datetime
  * *Text* fields are properly formatted

### 🧾 Summary:

This completes a clean, structured, and analysis-ready version of the dataset. The cleaned data will now support accurate analysis, visualization, and modeling.
