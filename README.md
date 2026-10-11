# Data Quality Toolkit

This toolkit focuses on six key dimensions of data quality—**Accuracy**, **Completeness**, **Uniqueness**, **Consistency**, **Timeliness**, and **Validity**—giving you a thorough overview of potential issues in your data and how to address them.



---

## Features

- **Completeness**: Identifies how many values are missing (null/NaN) and calculates the percentage of missing records per column.  
- **Uniqueness**: Flags duplicate rows or records (optionally, based on select columns).  
- **Validity**: Checks formatting and ranges (e.g., regex for emails, numeric limits for height).  
- **Accuracy**: Verifies real-world plausibility (e.g., checking if height is in a realistic range).  
- **Consistency**: Compares related fields (like `Age` vs. `DateOfBirth`) to identify logical mismatches.  
- **Timeliness**: Ensures records are up-to-date by comparing `LastUpdated` to a threshold date.

---

## Requirements

- **Python 3.7+**  
- [**pandas**](https://pandas.pydata.org/) (for data manipulation)  
- [**numpy**](https://numpy.org/) (for numerical operations)  
- **datetime** (standard Python library)

You can install the external dependencies using:

```bash
pip install pandas numpy
```



