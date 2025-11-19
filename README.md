# Sales-Analysis

## AIM:

To perform Data Cleaning, Exploratory Data Analysis (EDA), Feature Encoding, Feature Scaling, Feature Selection, and Data Visualization using Matplotlib and Seaborn for the given Sales Data CSV file.

## ALGORITHM:
### STEP 1: Import Required Libraries

Import libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn modules for preprocessing and feature selection.

### STEP 2: Load the CSV File

Read the Sales Data.csv file into a pandas DataFrame using:

df = pd.read_csv(file_path)

### STEP 3: Perform Data Cleaning

Remove duplicate rows

Fill missing values using forward fill

Convert Order Date to datetime format

Extract additional features like Month and Hour

### STEP 4: Exploratory Data Analysis (EDA)

Perform basic data inspection:

Statistical summary

Null value checking

Data types identification

### STEP 5: Feature Encoding

Apply One-Hot Encoding for categorical variables such as City and Product using:

pd.get_dummies()

### STEP 6: Feature Scaling

Use StandardScaler to normalize selected numerical columns like:

Quantity Ordered

Price Each

Sales

Hour

### STEP 7: Feature Selection

Use SelectKBest with f_regression to find top features impacting the Sales variable.

### STEP 8: Data Visualization using Matplotlib

Generate plots to understand trends over time:

Line plot for Sales by Month

Line plot for Sales by Hour

### STEP 9: Data Visualization using Seaborn

Use seaborn to create statistical graphics such as:

Scatterplot for Quantity vs Price

Barplot showing Sales by City

Heatmap showing feature correlations

### STEP 10: Interpret Results

Analyze each graph to understand trends like:

Peak sales months

Hours with highest purchases

Relationship between product price and quantity

Cities contributing most to revenue

## Program and Output:

<img width="1381" height="853" alt="Screenshot 2025-11-19 183127" src="https://github.com/user-attachments/assets/c65fbb3b-90fb-4d72-a2f8-76640742eaeb" />

<img width="1269" height="847" alt="Screenshot 2025-11-19 183159" src="https://github.com/user-attachments/assets/dd246941-67b8-445b-a7cf-dc2320e874f7" />

<img width="1234" height="844" alt="Screenshot 2025-11-19 183218" src="https://github.com/user-attachments/assets/f0e8e7ba-94a5-46d6-b63b-dbb8d3ca1068" />

<img width="1204" height="843" alt="Screenshot 2025-11-19 183242" src="https://github.com/user-attachments/assets/5e8cc965-cfe9-46eb-8327-a92493d081c7" />

<img width="1117" height="769" alt="Screenshot 2025-11-19 183259" src="https://github.com/user-attachments/assets/a2771ccf-a64d-4669-b683-1be00a48144d" />

<img width="1110" height="834" alt="Screenshot 2025-11-19 183341" src="https://github.com/user-attachments/assets/57a8b9eb-f012-442f-b9bb-c733f9658b95" />

## Result:
All required operations—data cleaning, EDA, encoding, scaling, feature selection, and visualization—were successfully performed.
The analysis provides meaningful insights into sales trends, customer buying patterns, and key factors affecting sales performance.


