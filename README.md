# 🏠 Airbnb Data Analysis using Python 

## 🔍 Key Insights

The exploratory analysis of the Airbnb dataset revealed several important patterns related to pricing, room types, neighbourhoods, and customer reviews.

### 💰 1. Listing Price Insights

- The average Airbnb listing price is approximately **$625**.
- The median listing price is approximately **$625**.
- Listing prices range from **$50 to $1,200**.
- The price distribution covers a wide range, indicating considerable variation in accommodation costs.
- The histogram shows that listings are distributed across different price ranges rather than being concentrated in one specific range.

---

### 🏠 2. Room Type Insights

The analysis identified four major room types:

- **Entire home/apt**
- **Private room**
- **Shared room**
- **Hotel room**

Key observations:

- **Entire home/apt** is the most common room type.
- **Private room** is the second most common category.
- **Shared room** listings represent a much smaller portion of the marketplace.
- **Hotel room** listings are the least represented category.

This indicates that Airbnb listings in the dataset are primarily focused on **entire homes/apartments and private rooms**.

---

### 📍 3. Neighbourhood Insights

The geographical analysis shows that Airbnb listings are highly concentrated in a few major neighbourhood groups.

The areas with the highest number of listings are:

1. **Manhattan**
2. **Brooklyn**
3. **Queens**

In comparison:

- **Bronx** has considerably fewer listings.
- **Staten Island** has the lowest number of listings.

This indicates that Airbnb activity is strongly concentrated in **Manhattan, Brooklyn, and Queens**.

---

### 💵 4. Price vs Room Type Insights

The box plot analysis was used to compare listing prices across different room types.

Key observations:

- Different room types show differences in their price distributions.
- The price ranges of the room types overlap considerably.
- **Shared rooms** and **hotel rooms** show different pricing patterns compared with private rooms and entire homes/apartments.
- Price alone does not completely distinguish the different room categories because there is considerable overlap between their distributions.

---

### ⭐ 5. Review Activity Insights

The number of reviews was analyzed over time using the `last review` date.

Key observations:

- Review activity varies across different periods.
- Noticeable spikes in review activity can be observed around **2019 and 2020**.
- Review activity is relatively low during several other periods.
- This indicates that customer engagement was not uniform throughout the entire timeline.

---

### 🧹 6. Data Quality Insights

The original dataset contained **102,599 records and 26 columns**.

During preprocessing:

- Missing values were identified across multiple columns.
- Rows with missing values in important fields such as `NAME` and `host name` were removed.
- `last review` was converted into a proper datetime format.
- Currency symbols were removed from `price` and `service fee`.
- Duplicate records were removed.
- Highly incomplete columns such as `license` and `house_rules` were removed.
- Inconsistent neighbourhood names such as `Brookln` and `Manhatan` were corrected.

After cleaning, the dataset contained:

**101,410 records and 24 columns.**

---

## 📈 Business Insights

The findings from the analysis can be useful for Airbnb hosts, property managers, and business analysts.

### 🏠 For Airbnb Hosts

- Hosts can compare their property type and pricing with the broader listing distribution.
- Understanding neighbourhood-level competition can help hosts evaluate their market position.
- Room type is an important factor when analyzing the pricing structure of listings.
- Hosts can consider location, room type, reviews, and availability when positioning their properties.

### 📍 For Property Managers

- **Manhattan, Brooklyn, and Queens** represent the largest listing markets in the dataset.
- These areas have a high concentration of Airbnb listings and may therefore represent highly competitive markets.
- Neighbourhood-level analysis can help property managers understand market concentration.
- Pricing and room-type analysis can support better property positioning.

### 👥 For Customers

- Customers have a wide range of accommodation prices to choose from.
- **Entire homes/apartments and private rooms** provide the majority of available options.
- Location and accommodation type are important factors when comparing Airbnb listings.
- The wide price range provides options for customers with different budgets.

### 📊 For Business Analysts

The analysis demonstrates that Airbnb's marketplace can be examined using factors such as:

- **Location**
- **Room type**
- **Listing price**
- **Customer review activity**

These variables can be further analyzed to understand marketplace behaviour and support data-driven decision-making.

---

## 📊 Summary of Major Findings

| Area | Key Finding |
|------|-------------|
| Original Dataset | 102,599 records |
| Final Dataset | 101,410 records |
| Original Columns | 26 |
| Final Columns | 24 |
| Average Price | ~$625 |
| Median Price | ~$625 |
| Price Range | $50 – $1,200 |
| Most Common Room Type | Entire home/apt |
| Second Most Common Room Type | Private room |
| Top Neighbourhood Group | Manhattan |
| Second Major Market | Brooklyn |
| Third Major Market | Queens |
| Lowest Listing Count | Staten Island |
| Review Trend | Activity varies over time |
| Main Analysis Areas | Price, Room Type, Location & Reviews |

---

## 💡 Overall Insight

The analysis shows that Airbnb listings are **geographically concentrated, dominated by entire homes/apartments and private rooms, and characterized by a broad range of listing prices**.

The strong concentration of listings in **Manhattan, Brooklyn, and Queens** highlights the importance of location in the Airbnb marketplace.

The analysis of room types shows that **entire homes/apartments and private rooms** make up the majority of listings, while shared rooms and hotel rooms represent a much smaller proportion.

The price analysis shows a wide range of accommodation costs, with listing prices ranging from **$50 to $1,200** and an average price of approximately **$625**.

The review analysis also shows that customer review activity changes over time, providing an opportunity for further investigation into customer engagement and marketplace behaviour.

Overall, this project demonstrates how **Python, Pandas, NumPy, Matplotlib, and Seaborn** can be used to clean real-world marketplace data, perform Exploratory Data Analysis, visualize important patterns, and generate meaningful business insights.

---

## 🚀 Future Scope

The analysis can be extended further by:

- Building an Airbnb price prediction model
- Performing neighbourhood-wise price analysis
- Conducting correlation and feature analysis
- Detecting and treating price outliers
- Performing customer review sentiment analysis
- Building an Airbnb recommendation system
- Creating an interactive Power BI dashboard
- Predicting listing demand
- Performing customer segmentation
- Analyzing host performance

---

## ⭐ If You Find This Project Useful

If you find this project useful or interesting, please consider giving the repository a ⭐ on GitHub.

Your support and feedback are highly appreciated!
