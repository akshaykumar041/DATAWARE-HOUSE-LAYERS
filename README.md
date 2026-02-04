# DATAWARE-HOUSE-LAYERS
This project uses a Medallion Architecture with ETL pipelines across Bronze, Silver, and Gold layers. Bronze stores raw source data, Silver cleans and standardizes it, and Gold delivers curated business-ready insights. This layered design ensures scalability, quality, and auditability.
# 🏗️ Data Warehouse Project: Bronze, Silver, Gold Layers

This project uses a **Medallion Architecture** with ETL pipelines to organize data into three layers: **Bronze, Silver, and Gold**.

---

## 🔹 Bronze Layer (Raw Data)
- Holds **raw data** exactly as ingested from sources (databases, APIs, files).
- Preserves original format for auditing and debugging.
- Purpose: Keep a reliable single source of truth.

---

## 🔸 Silver Layer (Cleaned Data)
- Contains **standardized and transformed data**.
- Cleansing, deduplication, and enrichment applied.
- Purpose: Provide **trusted datasets** ready for analytics.

---

## 🟡 Gold Layer (Business Data)
- Stores **curated, aggregated data** for reporting and dashboards.
- Examples: KPIs, customer views, financial summaries.
- Purpose: Deliver **business-ready insights**.

---

## ⚙️ ETL Flow
1. **Extract** → Load raw data into Bronze.  
2. **Transform** → Clean and enrich into Silver.  
3. **Load** → Aggregate and publish in Gold.  

---

## 📊 Benefits
- **Scalable**: Easy to add new sources.  
- **Quality**: Each layer improves trust.  
- **Flexible**: Analysts can use the right layer.  
- **Auditable**: Raw data always preserved.  
