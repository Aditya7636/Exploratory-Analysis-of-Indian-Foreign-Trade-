# 📊 Exploratory Analysis of Indian Foreign Trade (2010 - 2022)

This project aims to analyze the trends and structure of India’s foreign trade from 2010 to 2022. Over the past two decades, exports and imports have played a crucial role in India's economy, reflecting the country’s increasing significance in the global market. This analysis delves into India's exports and imports by examining trade balance trends, major trading partners, key commodities, and changes in trade composition over time.

---

## 🏆 Objectives of the Study

The main objectives of this study are to:
1. **Analyze the Growth of Exports, Imports, and Trade Balance**: Explore how India’s trade balance has evolved over the years.
2. **Identify Principal Commodities**: Discover key commodities that India exports and imports, with details down to 2, 4, 6, and 8-digit HS code levels.
3. **Examine Country-wise Trade Patterns**: Identify top countries for imports and exports, and understand their importance to India’s trade.
4. **Evaluate Profit-making Commodities**: Assess which commodities contribute positively to India’s trade balance.
5. **Track Value Trends Over Time**: Analyze commodities whose trade value has increased or decreased over the years.

---

## 📄 About the Dataset

The dataset was scraped using **Selenium WebDriver** from the Department of Commerce, Government of India. It consists of two files:

1. **export.csv**: Contains export data from 2010 to 2022 (up to April 2022).
2. **import.csv**: Contains import data for the same period.

**Dataset Summary**:
- **Export Data**: 138,714 records
- **Import Data**: 77,616 records

### Columns in the Dataset

- **HSCode**: Harmonized System code for commodities.
- **Commodity**: The specific commodity traded.
- **Value**: Value of exports or imports in million US dollars.
- **Country**: Country exported to (for exports) or imported from (for imports).
- **Year**: Year of the trade, ranging from 2010 to 2022.

---

## 🔍 Exploratory Data Analysis (EDA)

This analysis examines:
- **Total Exports, Imports, and Trade Balance Trends**: Visualize the year-on-year growth in exports, imports, and India’s trade balance.
- **Major Commodities in Trade**: Identify and visualize top commodities in terms of trade value and volume, along with their growth trends.
- **Key Trading Partners**: Analyze top countries that contribute to India’s trade, highlighting shifts over time.
- **Profitability by Commodity**: Identify commodities with the highest net exports (exports - imports), as well as those that may need attention due to high net imports.

---

## 📈 Analysis & Insights

This project aims to highlight:
1. **Growth Trends**: Identify significant growth patterns in exports, imports, and the trade balance.
2. **Key Commodities and Partners**: Uncover the most significant commodities and countries in India’s foreign trade.
3. **Economic Indicators**: Explore data that offers insights into India's economic health and dependencies in international trade.

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Exploratory-Analysis-of-Indian-Foreign-Trade.git
cd Exploratory-Analysis-of-Indian-Foreign-Trade
```

### 2. Install Dependencies

Install the necessary libraries listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 3. Load the Data

Make sure `export.csv` and `import.csv` are in the `/data` directory in your project root. These files contain the trade data for analysis.

---

## 🖥️ Usage

Run the analysis script to generate insights and visualizations:

```bash
python src/analysis.py
```

### Key Scripts and Files

- **src/analysis.py**: Main script for running the analysis.
- **data/**: Folder containing `export.csv` and `import.csv`.
- **notebooks/**: Jupyter notebooks for exploratory data analysis and visualization.

---

## 📊 Visualizations

Some of the visualizations you can expect from this analysis:
1. **Yearly Growth of Exports and Imports**: Line charts showing trends from 2010 to 2022.
2. **Top Trading Partners**: Bar charts for countries that contribute most to India’s imports and exports.
3. **Major Commodities by Trade Value**: Detailed analysis of top commodities.
4. **Trade Balance Analysis**: Visualization of net exports and imports by commodity type.
5. **Commodity Value Trends**: Heatmaps showing commodities with increased or decreased trade value over the years.

---

## 📝 Conclusion

The analysis will provide valuable insights into:
- India’s overall trade growth and balance trends.
- Structural changes in the composition of trade.
- Key commodities and countries contributing to India’s economic landscape.
- Insights into trade profitability and dependencies on specific trading partners.

---

## 🤝 Contributing

Contributions are welcome! Here’s how you can help:
1. Fork the repository.
2. Create a new branch with your feature (`git checkout -b feature-name`).
3. Commit your changes and submit a pull request.

---
