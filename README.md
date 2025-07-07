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

  ### Charts Created  
1. Bar Chart: Average Discount by Category  
   - Finding: Office products had deeper discounts than Electronics.  
2. Scatter Plot: Rating vs. Discount %  
   - Finding: No strong correlation—high discounts didn’t always mean low ratings.  
3. Doughnut Chart: Price Bucket Distribution  
   - Finding: 61% of products were under ₹500.

## **5. Strategic Recommendations**  
 **For Marketing Teams:**  
   - Capitalize on high discounts in **Cables & Accessories** to clear inventory.  
   - Highlight **top-rated Smart TVs** (avg. 4.3/5) in campaigns to leverage customer trust.  

 **For Pricing Strategy:**  
   - Test **targeted discounts (30-40%)** for high-revenue categories to balance profitability and sales volume.  
   - Expand mid-tier product lines (₹200–₹500) to meet concentrated demand.

## **6. Appendix**  
### **Dataset Overview**  
| **Field**          | **Description**                     | **Example**        |  
|---------------------|-------------------------------------|--------------------|  
| `product_id`        | Unique identifier                   | B07JW9H4J1         |  
| `category`          | Product classification              | Smart TVs          |  
| `discount_%`        | Discount offered (decimal)          | 0.55               |  
| `rating`            | Customer rating (1-5 scale)         | 4.2                |  
| `review_count`      | Total customer reviews              | 24,269             |  

### **Skills Demonstrated**  
i. **Data Wrangling:** Cleaning, standardization, and validation.  
ii. **Advanced Analytics:** PivotTables, correlation analysis, and segmentation.  
iii. **Visual Storytelling:** Charts and actionable insights.  
iv. **Business Acumen:** Linking data trends to strategic recommendations. 

## **7. Portfolio Presentation**  
📊 **Visual Preview:**  
*(Embed a screenshot of your Excel dashboard or charts here)* 
![DASHBOARD_page-0001](https://github.com/user-attachments/assets/47e2718f-23d8-4a4c-abe5-3c4cddad8734)
