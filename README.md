# Matplotlib Data Visualization Notebook

## Overview
This Jupyter notebook provides a comprehensive introduction to **matplotlib**, a powerful plotting library in Python. It covers everything from basic plotting concepts to advanced visualization techniques using real-world datasets.

## Contents

### 1. Introduction to Matplotlib
- Understanding the difference between `plt.plot()` and `plt.show()`
- Creating figures and axes using three methods:
  - Method 1: `plt.figure()` + `fig.add_subplot()`
  - Method 2: `plt.figure()` + `fig.add_axes()`
  - Method 3: `plt.subplots()` (recommended)

### 2. Basic Plot Types
- **Line plots** - using numpy arrays
- **Scatter plots** - with exponential and sine functions
- **Bar charts** - horizontal and vertical
- **Histograms** - with customizable bin sizes
- **Subplots** - creating multiple plots in one figure

### 3. Working with Real Data
#### Car Sales Dataset
- Data cleaning and preprocessing
- Converting string prices to numeric values
- Adding date ranges and cumulative sales
- Visualizing total sales over time
- Scatter plots showing odometer vs price

#### Heart Disease Dataset
- Exploring medical data
- Age distribution histograms
- Correlation between age and cholesterol
- Scatter plots with color coding by target variable
- Multi-plot layouts for comparative analysis

### 4. Advanced Visualization Techniques
- **Subplot layouts** (2×2 grids)
- **Customizing plots** with:
  - Titles, labels, and legends
  - Axis limits and ranges
  - Horizontal lines (mean values)
  - Color maps
- **Plotting from Pandas DataFrames** directly
- **Styling with built-in matplotlib styles** (`seaborn-v0_8`, `seaborn-v0_8-whitegrid`, etc.)

### 5. Object-Oriented vs Pyplot Methods
- Understanding when to use pyplot (quick plots) vs OO method (advanced customization)
- Building complete figures from scratch
- Creating professional-quality visualizations

## Key Learnings
1. **Three ways to create plots** with matplotlib
2. **Data cleaning** for visualization (removing $, commas, etc.)
3. **Multiple plot types** and when to use them
4. **Subplots** for comparative analysis
5. **Customization** techniques for publication-ready figures
6. **Pandas integration** for streamlined plotting
7. **Styling options** to enhance visual appeal

## Example Visualizations Created
- Line plots of mathematical functions
- Scatter plots of real-world medical data
- Bar charts of product prices
- Histograms of age distributions
- Time series of cumulative sales
- Multi-panel figures comparing health metrics

## Technologies Used
- **Python 3**
- **Matplotlib** - primary plotting library
- **NumPy** - numerical operations
- **Pandas** - data manipulation and DataFrame plotting
- **CSV datasets** - car sales and heart disease data

## Who This Notebook Is For
- Data science beginners learning visualization
- Python developers transitioning to data analysis
- Anyone wanting to create professional plots with matplotlib
- Students working with real datasets

## Key Takeaways
- Master the object-oriented approach for full control over your plots
- Learn to clean data before visualization
- Use subplots for comparing multiple variables
- Customize every element of your plots (titles, labels, colors, legends)
- Apply styles for consistent, professional-looking figures

## Usage
Run the notebook cells sequentially to see each visualization technique in action. The notebook includes both basic examples and real-world applications with downloadable datasets.

---

