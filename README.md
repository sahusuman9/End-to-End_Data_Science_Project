# 💻 Laptop Price & Trend Analysis from an Online Tech Store

An end-to-end data science project that scrapes laptop product data from a public e-commerce test site, cleans and transforms the dataset, performs exploratory data analysis with Python, and visualizes insights using both Python and Power BI.

---

## 🌐 Source Website

Data scraped from the publicly available and safe-to-scrape demo e-commerce site:  
🔗 [https://webscraper.io/test-sites/e-commerce/static/computers/laptops](https://webscraper.io/test-sites/e-commerce/static/computers/laptops)

---

## 🎯 Project Objectives

- 🕷️ Scrape laptop product data (title, price, rating, reviews, description, and image).
- 🧹 Clean and normalize raw data.
- 🔄 Transform data to add features like price category and rating quality.
- 📊 Visualize insights using Python libraries.
- 📈 Build an interactive Power BI dashboard.
- 📁 Create a fully documented GitHub-ready project.

---

## 🛠️ Tech Stack

| Task                 | Tools & Libraries                          |
|----------------------|---------------------------------------------|
| Web Scraping         | `requests`, `BeautifulSoup`                |
| Data Wrangling       | `pandas`, `numpy`, `re`                    |
| Visualization        | `matplotlib`, `seaborn`, `plotly`          |
| Dashboarding         | `Power BI`                                 |
| Documentation        | `Jupyter Notebook`, `Markdown`, `Git`      |

---

## 📥 Installation & Setup

Follow the steps below to set up and run this project on your local machine.

---

### 🔁 1. Clone the Repository

```bash
git clone https://github.com/yourusername/laptop-price-trend-analysis.git
cd laptop-price-trend-analysis
```

---

### 🌐 2. Run the Web Scraper

Open the Jupyter Notebook and scrap the data:

```bash
jupyter notebook notebooks/scraper.ipynb
```

---

### 🧼 3. Clean & Transform the Data

Open the Jupyter Notebook and follow the preprocessing steps:

```bash
jupyter notebook notebooks/analysis.ipynb
```

This includes:
- Data Cleaning  
- Feature Engineering (`Price_Category`, `Highly_Rated`)  
- Exporting cleaned data to: `data/processed/laptop_data_cleaned.csv`

---

### 📊 4. Explore Power BI Dashboard

Use the cleaned dataset to explore the insights visually.

```bash
Open: powerbi/dashboard.pbix
```

Includes:
- KPI cards  
- Price & Rating trends  
- Slicers for interactive filtering  
- Category-wise summary matrix

## 👤 Author
Suman Kumar Sahu
- 📧 sumankumarsahu7900@gmail.com
- 🔗 Linkedin: https://www.linkedin.com/in/suman-sahu-78b601219/
- 🔗 GitHub: https://github.com/sahusuman9
