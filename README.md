# Cultural-Informatics-and-Heritage-Portfolio

## Project: Data Normalization of Shanxi Jin Opera
This project demonstrates my ability to process heterogeneous intangible heritage data using "OpenRefine".

### 1. Data Source
- `Jin Opera basic data.csv`: Original records collected from Baidu Encyclopedia, containing inconsistencies in temporal formats.

### 2. Cleaning Process (The "How-To")
- Clustering: Used the "Levenshtein distance" algorithm to merge variant names of "Jin Opera" and found no problems.
- GREL Transformation: Normalized date formats using GREL expressions.

### 3. Results
- `cleaned-Jin-Opera-basic-data.csv`: The finalized structured dataset.
- `operations.json`: The full reproducibility script of the cleaning process.
