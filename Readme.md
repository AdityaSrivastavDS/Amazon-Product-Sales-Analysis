# 📊 Amazon Product Sales Analysis in Excel

Welcome to the **Amazon Product Sales Analysis** project! This project provides insights into product performance across various categories on Amazon using Excel. It demonstrates data cleaning, transformation, and visualization techniques to discover meaningful business patterns.

---

## 🧠 Project Objective

To analyze Amazon product sales data to determine:
- 🏆 The most sold product categories  
- ⭐ The highest-rated product categories  
- 💰 Insights on Amazon's profit or loss based on price differences

---

## 🔍 Steps Performed

### ✅ Step 1: Unused Column Removal

To clean the dataset and reduce noise, the following irrelevant columns were **removed**:

- `about_product` – Description of the product  
- `Username` – Already have `user_id`  
- `review_id` – Review ID not useful for analysis  
- `review_title` – Short review text  
- `review_content` – Long review text  
- `img_link` – Product image link  
- `product_link` – Link to the product page  
- `product_name` – Redundant for category-level analysis  
- `product_id` – Already identified by category and price  

🎯 **Remaining columns used for analysis:**

1. `category` – Product Category  
2. `discounted_price` – Price after discount  
3. `actual_price` – Original price  
4. `discount_percentage` – Discount in %  
5. `rating` – Product rating  
6. `rating_count` – Number of ratings  
7. `user_id` – User identifier  

---

### ✏️ Step 2: Renaming Columns

Renamed columns for better readability and formatting.  
Example: `discounted_price` ➡️ `Discounted Price`

---

### 🔁 Step 3: Replacing Values

Simplified lengthy category names into readable formats.  
🎯 **Final 9 Product Categories:**

- 🖥️ Computers & Accessories  
- 📱 Electronics  
- 🏠 Home & Kitchen  
- 🧸 Toys & Games  
- 🖨️ Office Products  
- 🔧 Home Improvement  
- 🚗 Car & Motorbike  
- 🧼 Health & Personal Care  
- 🎸 Musical Instruments  

---

### 🔢 Step 4: Values Formatting

- Rounded off all **decimal values** for clarity  
- Improved **data visualization** and consistency  

---

### 📈 Step 5: Pivot Table Creation

Created a **Pivot Table** to analyze:
- 📊 **Sum of `rating_count`** by each `Product Category`
- 🔍 Added **filters based on product rating**

✨ This helps identify:
- 🔝 Top-selling product categories
- 👥 Categories with the highest customer engagement

---

## 📌 Tools Used

- Microsoft Excel 🧮  
- Pivot Tables & Charts 📉  
- Data Cleaning and Transformation Features 🧼  

---

## 📚 Learnings & Takeaways

- Efficient data cleaning enhances clarity and performance  
- Visualizations provide quick business insights  
- Pivot tables are powerful for aggregated analysis  

---

## 🚀 Future Scope

- Incorporate **time-based sales trend** analysis  
- Perform **correlation analysis** between rating and price  
- Extend to **Power BI** or **Python** for dynamic dashboards

---

## 🤝 Let's Connect!

If you liked this project or want to collaborate on something similar, feel free to reach out!

---

**Made with 💙 in Excel**

