# DSA2040A — OLAP Assignment

This project demonstrates OLAP concepts using a synthetic sales dataset with SQLite and Pandas. It covers:
- ROLAP: SQL queries for relational aggregation
- MOLAP: Pandas pivot tables for multi-dimensional cubes
- HOLAP: Hybrid approach combining SQL detail with Pandas summaries
- OLAP operations: Slice, Dice, Roll-Up, Drill-Down

## 📊 Schema

- **products**: product_id, category, name, price  
- **dates**: date, year, quarter, month  
- **sales**: sale_id, date, product_id, quantity, revenue, promotion_applied

## 🚀 How to Run

1. Clone the repo: `git clone https://github.com/<your-username>/DSA2040A_OLAP_Assignment`
2. Open `olap_assignment.ipynb` in Jupyter Notebook
3. Run all cells sequentially
4. Ensure Python environment includes: pandas, numpy, matplotlib, seaborn, sqlite3

## 🧠 OLAP Implementation Summary

- **ROLAP**: SQL queries for average revenue, total sales, best-sellers
- **MOLAP**: Pandas pivot table for category × year revenue cube
- **HOLAP**: SQL filter + Pandas groupby for promo revenue by quarter
- **Operations**:
  - Slice: Filter by year
  - Dice: Filter by year + quarter + category
  - Roll-Up: Aggregate product → category → year
  - Drill-Down: Break down year → quarter → month

## 📈 Visuals

- Bar chart: Total revenue by category
- Heatmap: Category × Year revenue

---
