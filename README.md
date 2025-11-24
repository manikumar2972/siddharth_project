# 📊 Siddharth Associates – Trade Data Cleaning & Analysis (Excel)

This repository contains the cleaned and structured version of the **Siddharth Associates Import Trade Dataset**, stored in **cleaned_data.xls**.  
The data has been fully processed for further analysis in Excel, Python, or Power BI.

---

## 📁 File Included  
### **cleaned_data.xls**
A cleaned, preprocessed, and analysis-ready dataset containing columns such as:

- **Date of Shipment**
- **HSN Code**
- **Goods Description**
- **Quantity**
- **Units**
- **Assessable Value (INR)**
- **Duty Paid (INR)**
- **Total Value (INR)**
- **Category / Sub-Category / Model (Parsed & Added)**
- **Numeric-cleaned fields with NaN handling**
- **Derived columns:** Year, Month, Quarter

---

## 🧼 Data Cleaning Performed

### ✔ Missing Value Handling
- Replaced invalid numeric values with `NaN`
- Filled non-critical empty fields (e.g., model, spec) with blank text
- Retained `NaN` for financial columns to ensure accurate aggregations

### ✔ Date Standardization
- Converted **Date of Shipment** into proper Excel datetime
- Created:
  - `Year`
  - `Month`
  - `Quarter`

### ✔ Numeric Cleaning (Important)
Applied transformations to:

- `Total Value (INR)`
- `Assessable Value`
- `Duty Paid (INR)`
- `Quantity`

Steps include:
- Removing commas, text, and symbols
- Converting string → numeric
- Handling nulls safely

### ✔ Goods Description Parsing
Extracted new structured fields:

- `model_name`
- `model_number`
- `capacity_spec`
- `material_type`
- `embedded_quantity`
- `unit_price_usd`

---

## 📊 Ready for Analysis In:
- **Excel** (PivotTables, Charts)
- **Python / Pandas**
- **Power BI Dashboarding**
- **SQL Data Import**

---

## 🚀 What You Can Build With This File
- Year-wise import trends  
- HSN-level duty analysis  
- Supplier contribution metrics  
- Category → Sub-category → Model breakdown  
- Unit economics & per-unit cost insights  
- Custom Power BI dashboards  

---

## 📬 Contact  
📧 **manikumar2972@gmail.com**  
🔗 **LinkedIn:** https://www.linkedin.com/in/manikumar-cheema  
