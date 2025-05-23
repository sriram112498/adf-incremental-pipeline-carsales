# 🚗 Azure Data Factory – Incremental ETL Pipeline for Car Sales Data

This project demonstrates an **incremental ETL pipeline** using **Azure Data Factory (ADF)** for ingesting car sales data into a modern data architecture with **Azure SQL Database**, **Databricks**, and **Delta Lake** layers.

## 📁 Repository Structure


---

## ⚙️ Technologies Used

- **Azure Data Factory**
- **Azure SQL Database**
- **Azure Databricks**
- **Delta Lake**
- **GitHub**

---

## 🔁 Incremental Load Logic

1. **Lookup Activities** (`last_load`, `current_load`)
2. **Copy Activity** – Transfers new data based on watermark
3. **Stored Procedure** – Updates the watermark post load
4. **Databricks Notebooks** – Process data into Silver and Gold layers
5. **Dimension & Fact Tables** – DimBranch, DimDealer, DimModel, DimDate, FactSales

---

## 📸 Visual References

All key ADF pipeline and config screenshots are in the `screenshots/` folder for easy understanding.

---

## 🧠 Author

**Sriram Srinivasan**  
MS in IT & Management @ UT Dallas  
GitHub: [sriram112498](https://github.com/sriram112498)

---

## 📜 License

MIT License (or choose your preferred license)

