# End-to-End SQL Analytics Project

This project demonstrates a complete SQL-based analytics workflow—from database creation to advanced reporting. Designed for data analysts and BI professionals, it provides a structured, modular approach to explore, analyze, and extract actionable insights from a sales dataset. Each SQL script focuses on a specific analytical task, showcasing best practices and real-world business logic.

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## ✅ What This Project Covers

📁 Database setup with star schema (dimensional modeling)

🔍 Exploratory data analysis (EDA) across dimensions and dates

📏 Aggregated metrics & KPIs (sales, quantity, orders, customers)

📈 Time-series and cumulative trend analysis

🚀 Performance tracking: YoY/MoM comparisons using window functions

🧠 Customer and product segmentation

📊 Executive-level reporting with KPIs and dynamic views

<pre> ## 🗂 Project Structure | File / View | Description | |----------------------------------|-------------| | `00_init_database.sql` | Creates and loads a full analytics database with dimensional tables. | | `01_database_exploration.sql` | Explores schema, table structures, and metadata. | | `02_dimensions_exploration.sql` | Analyzes unique values in customer and product dimensions. | | `03_date_range_exploration.sql` | Examines time coverage and customer age distribution. | | `04_measures_exploration.sql` | Computes high-level KPIs: total sales, orders, quantities, etc. | | `05_magnitude_analysis.sql` | Breaks down key metrics by categories like gender, country, and product. | | `06_ranking_analysis.sql` | *(Optional next step: top N analysis, etc.)* | | `07_change_over_time_analysis.sql` | Analyzes sales and customer trends over time. | | `08_cumulative_analysis.sql` | Builds cumulative KPIs using window functions. | | `09_performance_analysis.sql` | Measures YoY performance using `LAG()` and `AVG()` windows. | | `10_data_segmentation.sql` | Segments customers and products based on behavior and cost tiers. | | `11_part_to_whole_analysis.sql` | Evaluates contribution to overall sales (percent of total). | | `12_report_customers.sql` | Creates a summary view of customer KPIs, segments, and behaviors. | | `13_report_products.sql` | Creates a view showing product performance, segmentation, and revenue metrics. | </pre>

## 🧠 Skills Demonstrated

SQL for data profiling and schema exploration

Dimensional modeling (star schema: fact + dimensions)

Aggregate & window functions (SUM(), LAG(), OVER())

Conditional logic with CASE for segmentation

Trend & cohort analysis

Report generation using SQL views

## 🌟 About Me

Hi, I’m a Logistics Systems Analyst with over 5 years of experience improving how distribution centers operate — one process, report, and system enhancement at a time.

I specialize in turning operational chaos into clarity, using tools like SQL, Manhattan WMS, and SAP S4 to uncover insights and implement solutions that make a real difference. From increasing system efficiency across multiple locations to leading cross-functional projects, I thrive where tech meets logistics.

What sets me apart? I don’t just analyze — I solve, optimize, and deliver. I’ve built tools that save hours of manual work, led initiatives that boosted productivity, and helped teams work smarter with data-backed decisions.

I'm currently open to opportunities where I can bring my technical and analytical skills to a collaborative, growth-focused environment. If you're looking for someone who understands the details but thinks big-picture, we should talk.

Let's stay in touch! Feel free to connect with me here:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/ricardovargas-contact)

### 🧰 Project Tech Stack
Microsoft SQL Server

