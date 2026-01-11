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

## 📝 Pushing to GitHub Repository

### Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and log in
2. Click the **"+"** icon in the top right corner
3. Select **"New repository"**
4. Enter repository name: `pandas` (or your preferred name)
5. Add a description (optional)
6. Choose **Public** or **Private**
7. **Do NOT** check "Initialize this repository with a README" (you already have files)
8. Click **"Create repository"**

### Step 2: Configure Git (First Time Only)

If you haven't configured git before, set your name and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Step 3: Initialize and Push Your Repository

Open PowerShell in your project directory and run these commands:

```bash
# Navigate to your project folder
cd c:\Users\memo\Desktop\ML\pandas

# Initialize git repository (if not already done)
git init

# Add all files to staging area
git add .

# Commit the files
git commit -m "Initial commit: Add pandas wine analysis notebook"

# Add your GitHub repository as remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/pandas.git

# Rename branch to main (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
```

### Step 4: Authenticate with GitHub

When you push for the first time, you'll be prompted to authenticate:
- Use your GitHub username
- For password, use a **Personal Access Token** (not your account password)

#### Creating a Personal Access Token:
1. Go to GitHub Settings → Developer settings → Personal access tokens → Tokens (classic)
2. Click "Generate new token" → "Generate new token (classic)"
3. Give it a name (e.g., "Pandas Project")
4. Select scopes: Check **"repo"** (full control of private repositories)
5. Click "Generate token"
6. **Copy the token** (you won't see it again!)
7. Use this token as your password when pushing

### Updating the Repository Later

After making changes to your notebook:

```bash
# Check what files have changed
git status

# Add all changes
git add .

# Commit with a descriptive message
git commit -m "Update: description of your changes"

# Push to GitHub
git push origin main
```

### Common Git Commands

```bash
# View commit history
git log --oneline

# Check current status
git status

# View remote repository URL
git remote -v

# Pull latest changes from GitHub
git pull origin main

# Create and switch to a new branch
git checkout -b feature-branch-name
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
