# Filter Companies By Year
A UiPath workflow that filters and merges company data from multiple Excel files. It handles both modern .xlsx files and legacy .xls files. <br>
The workflow reads company information, applies filters based on founding year, and outputs a combined DataTable containing only the relevant companies.

## ✨ Features
- Reads data from .xlsx and .xls Excel files.
- Filters companies founded before 2005.
- Combines filtered data into a single DataTable.
- Writes the filtered data to an output Excel file.
- Handles legacy Excel files using Excel Application Scope where required.

## 📋 Requirements
- UiPath Studio
- UiPath.Excel.Activities package

## ⚙️ Setup
1. Clone or download this repository.
2. Open the project in UiPath Studio.
3. Ensure the Data folder contains the source Excel files (`Data1.xlsx` and `Data2.xls`).
4. Open the `Main.xaml` file.
5. Run the workflow. The filtered data will be written to `Output\CompaniesBefore2005.xlsx`.
