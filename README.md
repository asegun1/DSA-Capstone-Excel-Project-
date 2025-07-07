# DSA-Capstone-Excel-Project-
This is where i started my Portfolio when taking my DSA Project

# **Amazon Product Sales Analysis**  
**Project:** Pricing, Discounts & Customer Reviews Analysis  
**Tools:** Microsoft Excel (PivotTablest, Data Visualization)  
**Dataset:** Amazon Electronics (Cables, Electronics, Computer& Accessories)

## **1. Project Overview**  
### **Objective**  
Analyzed Amazon product data to identify pricing trends, discount effectiveness, and customer satisfaction across categories to support strategic decision-making.

### **Key Business Questions**  
- How do discounts vary by product category, and which segments offer the deepest markdowns?
- Which categories have the highest customer ratings, and how do they correlate with pricing?
- What is the revenue potential (price × engagement) of top-performing products?
- How are products distributed across price ranges, and where is demand concentrated?

## **2. Data Preparation & Cleaning**  
### **Approach**  
🔹 **Removed Duplicates:** Ensured data integrity by eliminating duplicate entries (`Data → Remove Duplicates`).  
🔹 **Handled Missing Values:** Replaced blank ratings with zeros to maintain accurate averages (`=IF(ISBLANK(), 0)`).  
🔹 **Standardized Data:**  
   - Corrected inconsistent naming (e.g., "Electornics" → "Electronics") using `=PROPER()`.  
   - Converted discount percentages to decimals for calculations (e.g., "64%" → `0.64`).  
🔹 **Validated Numerical Fields:** Flagged pricing outliers with Conditional Formatting to ensure data reliability.

## **3. Analytical Techniques**  
| **Insight**                  | **Method**                          | **Tools Used**               |  
|-------------------------------|-------------------------------------|-------------------------------|  
| Unique Product Count          | Distinct Count in PivotTable        | Power Pivot Data Model        |  
| Discount vs. Rating Analysis  | Scatter Plot + Correlation          | `=CORREL()`                   |  
| Revenue Potential             | Calculated Field (`Price × Reviews`)| PivotTable Summarization      |  
| Price Tier Segmentation       | Conditional Bucketing               | `=IF()` + PivotTable Groups   |

