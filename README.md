# Pixar-Films
 Pixar films challenge exploratory analysis

# Data Handling and Integrity
All CSV files in this repository (e.g., public_response.csv, academy.csv, etc.) represent the raw data exactly as it was originally provided. The Jupyter Notebooks included here perform in-memory data exploration and transformations:

In-Memory Changes Only:
The notebooks load the CSV files into pandas DataFrames. Any modifications—such as data cleaning, transformations, or analysis—occur only in memory. The original CSV files are not overwritten by default.

Persisting Changes:
If you wish to save the modified DataFrames back to CSV, the notebooks include code (using DataFrame.to_csv()) that you must explicitly run. Otherwise, the CSV files on disk remain unchanged.

Why This Matters:
This approach ensures that the raw data stays intact for reproducibility. Users running the notebooks will always start with the exact same input data as provided in this repository.

[Project](https://mavenanalytics.io/project/30567)
