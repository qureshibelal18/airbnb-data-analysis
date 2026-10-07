# 🏠 Airbnb Data Analysis & Exploratory Data Analysis

## 📌 Project Overview

This project performs an in-depth **Exploratory Data Analysis (EDA)** on an Airbnb listings dataset to understand pricing patterns, room-type distribution, neighbourhood-wise listings, and review trends.

The project focuses on transforming raw Airbnb data into meaningful insights through **data cleaning, preprocessing, statistical analysis, and visualization using Python**.

The analysis helps understand how factors such as **room type, location, listing price, and reviews** vary across Airbnb properties.

---

## 🎯 Objectives

The main objectives of this project are:

- Perform data cleaning and preprocessing
- Identify and handle missing values
- Remove duplicate records
- Convert incorrect data types into appropriate formats
- Analyze listing price distributions
- Understand the distribution of different room types
- Analyze Airbnb listings across neighbourhood groups
- Study the relationship between room type and price
- Analyze the number of reviews over time
- Generate meaningful business insights from the dataset

---

## 📊 Dataset

The dataset contains Airbnb listing information with details about:

- Property and host information
- Neighbourhood and geographical information
- Room types
- Listing prices
- Service fees
- Minimum nights
- Number of reviews
- Review ratings
- Availability
- Cancellation policies
- Host verification
- Construction year

### Dataset Size

**Initial Dataset:**
- Rows: `102,599`
- Columns: `26`

**After Data Cleaning:**
- Rows: `101,410`
- Columns: `24`

The original dataset contained columns such as `id`, `NAME`, `host id`, `host_identity_verified`, `host name`, `neighbourhood group`, `neighbourhood`, `lat`, `long`, `room type`, `price`, `service fee`, `minimum nights`, `number of reviews`, `last review`, `reviews per month`, `review rate number`, and `availability 365`.

---

## 🛠️ Technologies & Libraries Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Environment
- Google Colab / Jupyter Notebook

---

## 🔄 Project Workflow

Raw Airbnb Dataset
        ↓
Data Loading
        ↓
Data Understanding
        ↓
Missing Value Analysis
        ↓
Data Cleaning
        ↓
Data Type Conversion
        ↓
Duplicate Removal
        ↓
Descriptive Statistics
        ↓
Exploratory Data Analysis
        ↓
Data Visualization
        ↓
Business Insights

## 🔍 Key Insights

The exploratory analysis of the Airbnb dataset revealed several important patterns related to pricing, room types, neighbourhoods, and customer reviews.

### 💰 1. Listing Price Insights

- The average Airbnb listing price is approximately **$625**.
- The median listing price is also around **$625**.
- Listing prices range from approximately **$50 to $1,200**.
- The price distribution covers a wide range, indicating considerable variation in accommodation costs.
- The histogram shows that listings are spread relatively evenly across the available price ranges rather than being concentrated in one particular range.

---

### 🏠 2. Room Type Insights

The analysis identified four major room types:

- **Entire home/apt**
- **Private room**
- **Shared room**
- **Hotel room**

Key observations:

- **Entire home/apt** is the most common room type in the dataset.
- **Private room** is the second most common category.
- **Shared room** listings represent a much smaller portion of the marketplace.
- **Hotel room** listings are the least represented category.

This suggests that Airbnb listings in the dataset are primarily focused on **entire homes/apartments and private rooms**.

---

### 📍 3. Neighbourhood Insights

The geographical analysis shows that Airbnb listings are highly concentrated in a few major neighbourhood groups.

The areas with the highest number of listings are:

1. **Manhattan**
2. **Brooklyn**
3. **Queens**

In comparison:

- Bronx has considerably fewer listings.
- Staten Island has the lowest number of listings among the major neighbourhood groups.

This indicates that Airbnb activity is strongly concentrated in **Manhattan, Brooklyn, and Queens**.

---

### 💵 4. Price vs Room Type Insights

The box plot analysis was used to compare listing prices across different room types.

Key observations:

- Different room types show differences in their price distributions.
- The price ranges of the room types overlap considerably.
- **Shared rooms** and **hotel rooms** show different pricing patterns compared with private rooms and entire homes/apartments.
- Price alone does not completely distinguish the different room categories, as there is considerable overlap in their distributions.

---

### ⭐ 5. Review Activity Insights

The number of reviews was analyzed over time using the `last review` date.

Key observations:

- Review activity varies significantly across different periods.
- Noticeable spikes in review activity can be observed around **2019 and 2020**.
- Review activity is relatively low during several other periods.
- This indicates that customer engagement was not uniform throughout the entire timeline.

---

### 🧹 6. Data Quality Insights

The original dataset contained **102,599 records and 26 columns**.

During preprocessing:

- Missing values were identified across multiple columns.
- Important text fields such as `NAME` and `host name` were cleaned by removing rows where these fields were missing.
- `last review` was converted into a proper datetime format.
- Currency symbols were removed from `price` and `service fee`.
- Duplicate records were removed.
- Highly incomplete columns such as `license` and `house_rules` were removed.

After cleaning, the dataset contained:

**101,410 records and 24 columns.**

---

## 📈 Business Insights

The findings from the analysis can be useful for Airbnb hosts, property managers, and marketplace analysts.

### For Airbnb Hosts

- Hosts can compare their property type and pricing with the broader listing distribution.
- Understanding neighbourhood-level competition can help hosts evaluate their market position.
- Room type plays an important role in understanding the pricing structure of listings.

### For Property Managers

- **Manhattan, Brooklyn, and Queens** represent the largest listing markets in the dataset.
- These areas may provide greater market activity but could also indicate stronger competition.
- Pricing and room-type analysis can support better property positioning.

### For Customers

- Customers have a wide range of accommodation prices to choose from.
- Entire homes/apartments and private rooms provide the majority of available options.
- Accommodation type and location are important factors when comparing listings.

### For Business Analysts

The analysis demonstrates that Airbnb's marketplace is influenced by:

- **Location**
- **Room type**
- **Listing price**
- **Customer review activity**

These variables can be further explored to understand marketplace behaviour and support data-driven decisions.

---

## 📊 Summary of Major Findings

| Area | Key Finding |
|------|-------------|
| Dataset Size | 102,599 → 101,410 records after cleaning |
| Average Price | ~$625 |
| Median Price | ~$625 |
| Price Range | $50 – $1,200 |
| Most Common Room Type | Entire home/apt |
| Second Most Common | Private room |
| Top Neighbourhood Group | Manhattan |
| Other Major Markets | Brooklyn & Queens |
| Lowest Major Market | Staten Island |
| Review Trend | Significant activity spikes around 2019–2020 |
| Main Analysis Areas | Price, Room Type, Location & Reviews |

---

## 💡 Overall Insight

The analysis shows that Airbnb listings are **geographically concentrated, dominated by entire homes/apartments and private rooms, and characterized by a broad range of listing prices**.

The strong concentration of listings in **Manhattan, Brooklyn, and Queens** highlights the importance of location in the Airbnb marketplace. At the same time, differences in room-type pricing and changes in review activity provide opportunities for deeper analysis.

This project demonstrates how **Python, Pandas, Matplotlib, and Seaborn** can be used to convert raw marketplace data into actionable insights through Exploratory Data Analysis.
