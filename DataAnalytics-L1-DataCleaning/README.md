# Customer Sales Data Cleaning Project

## Oasis Infobyte Data Analytics Internship

### Level 1 — Task 3: Cleaning Data

## Project Overview

This project demonstrates a complete professional data-cleaning workflow using a deliberately messy customer sales dataset.

The objective was to transform inconsistent and incomplete raw data into a clean, reliable and analysis-ready dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Cleaning Process

The project includes:

- Initial data inspection
- Data-quality reporting
- Exact duplicate removal
- Column-name standardisation
- Gender standardisation
- City and country standardisation
- Age cleaning and validation
- Missing-value treatment
- Date conversion
- Invalid purchase amount treatment
- Feedback score validation
- Customer ID quality checks
- IQR-based outlier detection
- Outlier capping
- Data-type correction
- Final missing-value audit
- Before-vs-after quality comparison
- Cleaned CSV export

## Missing Value Strategy

Different variables were treated according to their data type and business meaning.

- Numerical age values were imputed using the median.
- Categorical variables such as gender, city and country were imputed using the mode.
- Missing dates were handled using the median valid date.
- Invalid purchase values were converted to missing values and replaced using the median purchase amount.
- Missing customer IDs were not statistically imputed because customer IDs are identifiers.

## Outlier Treatment

Potential purchase amount outliers were identified using the Interquartile Range (IQR) method.

Instead of deleting the records, extreme values were capped at the calculated IQR boundaries.

This approach preserved customer records while reducing the statistical influence of unusually extreme values.

## Final Output

The cleaned dataset was exported as:

`cleaned_customer_sales_data.csv`

## Key Learning Outcome

This project demonstrates that data cleaning is not simply removing errors.

Each cleaning decision should consider the meaning of the variable, the potential impact on later analysis and whether information can be retained without reducing data quality.

## Files

- `Data_Cleaning_Project.ipynb`
- `cleaned_customer_sales_data.csv`

## Author

Ty

## Internship

Oasis Infobyte — Data Analytics Internship
