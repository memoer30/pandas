# Wine Reviews Data Analysis with Pandas

A comprehensive Jupyter notebook tutorial for learning pandas data analysis using the Wine Magazine dataset (130k wine reviews).

## 📋 Description

This notebook provides a hands-on introduction to pandas, covering fundamental data manipulation and analysis techniques using real-world wine review data from Wine Magazine. The dataset contains 129,971 wine reviews with 13 different attributes including country, price, points, variety, and taster information.

## 📊 Dataset

- **File**: `winemag-data-130k-v2.csv`
- **Size**: 129,971 wine reviews
- **Columns**: 13 attributes
  - country, description, designation, points, price, province
  - region_1, region_2, taster_name, taster_twitter_handle
  - title, variety, winery

## 🎯 Topics Covered

### 1. Data Structures
- Creating DataFrames and Series
- Reading CSV files
- Setting index columns

### 2. Data Selection & Indexing
- Using `.iloc[]` for integer-based indexing
- Using `.loc[]` for label-based indexing
- Column selection methods
- Boolean indexing

### 3. Data Filtering
- Conditional filtering
- Using `isin()` and `notnull()`
- Combining multiple conditions with `&` and `|`

### 4. Data Manipulation
- Adding new columns
- Mapping and applying functions
- Using `lambda` functions
- Built-in operations

### 5. Grouping & Aggregation
- `groupby()` operations
- Aggregation functions (count, min, max, mean)
- Multi-index handling
- Sorting data

### 6. Data Types & Missing Values
- Type conversion with `astype()`
- Handling missing data with `fillna()`
- Replacing values with `replace()`
- Detecting null values

### 7. Renaming & Restructuring
- Renaming columns and indices
- Renaming axes
- Resetting indices

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy jupyter
```

### Running the Notebook

1. Clone the repository
2. Navigate to the project directory
3. Launch Jupyter Notebook:
```bash
jupyter notebook introduction_to_pandas.ipynb
```



## 📂 Project Structure

```
pandas/
├── introduction_to_pandas.ipynb    # Main Jupyter notebook
├── winemag-data-130k-v2.csv       # Wine reviews dataset
├── README.md                       # This file
└── anaconda_projects/              # Anaconda project files
    └── db/
```

## 🔍 Key Learning Outcomes

- Master DataFrame and Series creation and manipulation
- Perform efficient data selection using iloc and loc
- Apply filtering techniques for data analysis
- Use groupby operations for aggregated insights
- Handle missing data and type conversions
- Restructure data with renaming and indexing operations

## 📈 Sample Insights from the Dataset

- Average wine rating: ~88 points
- Total reviews: 129,971
- Countries represented: 44
- Price range: $4 - $3,300
- Most reviewed varieties: Pinot Noir, Chardonnay, Cabernet Sauvignon

## 🛠️ Troubleshooting

### Large File Warning
If you get a warning about the CSV file being too large:
```bash
git lfs install
git lfs track "*.csv"
git add .gitattributes
```

### Authentication Failed
- Make sure you're using a Personal Access Token, not your password
- Check that your token has the correct permissions (repo access)

### Permission Denied
- Verify you have write access to the repository
- Check that the remote URL is correct: `git remote -v`

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements!

## 📄 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

- Wine Magazine for providing the dataset
- Pandas development team for the excellent library

---

**Happy Learning! 🍷📊**
