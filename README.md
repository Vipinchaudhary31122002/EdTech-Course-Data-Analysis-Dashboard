# EdTech Course Data Analysis Dashboard

A **Power BI** dashboard that transforms online course data into actionable insights—covering engagement metrics, language trends, and instructor performance.

---

## 🧩 Project Highlights

- **Source Data**
  - Demo dataset from Kaggle (~45 columns: titles, categories, language, subtitles, ratings, views, skills, instructors, and more)
- **Data Prep**
  - Cleansing: filtering out blanks, errors, duplicates
  - Type conversion and formatting (e.g. ratings cast to decimal)
- **Dashboard Elements**
  - Slicers: filter by category, sub-category, language
  - Visuals: bar charts, heatmaps, scatter plots
  - Drill-through: focus on top skills, instructors, subtitles vs. views
- **Key Insights**
  - Which course categories have the highest engagement
  - Impact of subtitles on views and reach
  - Most popular skills and top-rated instructors
- **Tools & Technologies**
  - Power BI Desktop
  - Power Query (M)
  - DAX Calculations
  - CSV/XLSX Data Source

---

## 🎯 Use Cases

- For **product managers** – determine which course categories or languages need expansion
- For **content teams** – assess subtitle and language strategies to boost engagement
- For **instructor support** – identify and promote high-impact educators

---

## 🚀 Getting Started

1. Clone repo or download Power BI `.pbix` file.
2. Open in **Power BI Desktop**.
3. Load the dataset (CSV/XLSX).
4. Let **Power Query** run refresh transformation steps.
5. Interact with slicers and visuals to explore insights.

---

## 🛠️ Data Refresh & Customization

- Source files are in `/data/`
- To include new data:
  1. Add new CSV(s)
  2. Edit or append queries in Power Query Editor
  3. Refresh dataset
- Customize by:
  - Adding visuals for new KPIs
  - Building custom DAX measures
  - Incorporating advanced filters or report themes

---

## 📚 Design Principles

- **Clear & Minimal Design** – follows best practices for dashboard readability: consistent flow, proximity grouping, minimal distractions :contentReference[oaicite:1]{index=1}
- **Narrative Structure** – starts with high-level KPIs, facilitates drill-down into categories, skills, and languages
- **Interactive by Design** – slicers allow dynamic exploration; focuses on exploratory analysis over static charts

---

## 📈 Dashboard Structure

| Page | Description                                      |
|------|--------------------------------------------------|
| Overview | Engagement metrics by category & language       |
| Instructor Analysis | Top instructors by ratings & views     |
| Skills Insights | Trending skills and subtitle impact      |

---

## 👥 Contributing

Contributions welcome via:
- Importing new datasets
- Suggesting new metrics or visuals
- Architectural / UI enhancements

Please open a PR or issue for feedback.
