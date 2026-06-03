# Split values for analytics
Created: 2026-06-03
Last update: 2026-06-03

## Description

Alma analytics only allows to enter a maximum of 9,999 values for analysis. Sometimes you need to enter values from a larger report.

This code will take the large file, and split the chosen column into discrete chunks of 9,999 values that can be copy-pasted onto Alma Analytics.

**NOTE: In testing, the output `.txt` file displays better in Notepad++ than regular Notepad**

## Open notebook in Google Collab

To use the notebook in Google collab:

[https://colab.research.google.com/github/r-antoniomg/split-values-for-analytics/blob/main/2026-06-03-split-file-for-analytics.ipynb](https://colab.research.google.com/github/r-antoniomg/split-values-for-analytics/blob/main/2026-06-03-split-file-for-analytics.ipynb)

## Related files

You can test this notebook with either of the synthetic data files provided:

* `2026-06-03-example-synthetic-data.csv`
* `2026-06-03-example-synthetic-data.xlsx`

**NOTE: The MMS Id and Barcode numbers provided are not real and will not work in Alma analytics. The files are meant to test the code for the purpose of splitting a large file into 9,999 value chunks.**
