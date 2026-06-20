# Basic Data Exploration and Cleaning using Pandas

## Objective

Perform basic data exploration and data cleaning using Pandas on the `jeans.csv` dataset.

## Dataset Used

* Input Dataset: `jeans.csv`
* Cleaned Dataset: `cleaned_jeans.csv`

## Tasks Performed

### 1. Data Loading

* Loaded the CSV dataset using Pandas.

### 2. Data Exploration

* Displayed first 5 rows using `head()`
* Displayed last 5 rows using `tail()`
* Checked dataset shape
* Viewed column names
* Examined data types

### 3. Missing Value Handling

Missing values were found in:

* discount
* what_customers_said
* seller_name
* videos
* seller_information
* variations

Actions performed:

* Numeric columns were filled using mean values.
* Text columns were filled with "Not Available".

### 4. Data Cleaning

* Checked for duplicate records.
* Removed duplicate rows if present.

### 5. Basic Operations

* Filtered products having rating greater than or equal to 4.

### 6. Derived Column Creation

The assignment requested creation of a derived column.

Since the dataset did not contain quantity information, a new column named `discount_amount` was created using:

discount_amount = initial_price * discount / 100

### 7. Output

Generated:

* `data_cleaning.ipynb`
* `cleaned_jeans.csv`

## Result

The dataset was successfully explored, cleaned, and saved as a new CSV file.
