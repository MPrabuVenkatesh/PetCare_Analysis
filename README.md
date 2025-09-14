# Pet Dog Data Analysis Project 🐶📊

This project explores pet dog adoption trends and related pet supply sales using **Python, SQL, and Power BI**.  
It combines three cleaned datasets:

- **Dog Breeds** – breed-level details (origin, longevity, traits, health issues).
- **Dog Descriptions** – adoption listings (58k records) with breed, age, size, and adoption status.
- **Pet Supplies** – 2k product listings with sales, ratings, and wishlist counts.

### 🔍 Goals
- Analyze adoption trends by breed, size, and longevity.
- Explore health/trait characteristics of popular breeds.
- Connect adoption data with pet supply sales using bridges (Pet Type and Size Category).
- Deliver a Power BI dashboard with interactive insights.

### 🛠 Tools Used
- **Python (pandas, matplotlib, SQLAlchemy)** – cleaning, preprocessing, and exporting data.  
- **SQL (DDL + queries)** – schema design and querying.  
- **Power BI** – modeling, DAX measures, and dashboards.  

### 📊 Key Insights
- Small and medium breeds dominate adoption listings.
- Average longevity clusters around 11–13 years.
- Products for **Small Dogs** outsell those for Large Dogs, aligning with adoption trends.
- Health issues and character traits show distinct patterns across breeds.

---

## 🔹 2. Suggested GitHub Repo Structure

```plaintext
pet-dog-analysis/
│
├─ data/                  # Original and cleaned datasets
│   ├─ cleaned_dog_breeds.csv
│   ├─ cleaned_dog_descriptions.csv
│   ├─ cleaned_pet_supplies.csv
│
├─ notebooks/             # Python Jupyter notebooks
│   ├─ 01_EDA_and_Cleanup.ipynb
│   ├─ 02_SQL_Export.ipynb
│   └─ 03_Visualization_Prep.ipynb
│
├─ sql/                   # SQL scripts
│   ├─ schema.sql         # CREATE TABLE scripts
│   ├─ queries.sql        # Sample analytical queries
│
├─ powerbi/               # Power BI files
│   └─ dog_dashboard.pbix # Your main Power BI dashboard
│
├─ outputs/               # Exported cleaned files or figures
│   ├─ fact_dog_descriptions.csv
│   ├─ fact_pet_supplies.csv
│   └─ summary_visuals.png
│
├─ README.md              # Project overview (intro, goals, results)
└─ requirements.txt       # Python dependencies
