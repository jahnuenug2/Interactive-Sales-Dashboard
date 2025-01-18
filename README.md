"Interactive Sales Dashboard built with HTML, JavaScript &amp; Plotly.js. Upload JSON files to generate dynamic sales insights. Includes revenue trends, customer analysis, and product performance charts."
# 📊 Interactive Sales Performance Dashboard

## 🔹 Overview
This project is an **Interactive Sales Performance Dashboard** built using **HTML, JavaScript, and Plotly.js**. It allows users to **upload a JSON file containing sales data**, which is then dynamically visualized using five key performance charts.

This dashboard provides deep insights into:
- **Sales trends over time**
- **Best-selling product lines**
- **Top customers by revenue**
- **Sales distribution by region**
- **Order status breakdown**

---

## 🔹 Features
✅ **Upload and Parse JSON Sales Data**  
✅ **Interactive Sales Charts with Plotly.js**  
✅ **Five Key Data Visualizations**:  
   - 📈 **Sales Revenue Over Time (Line Chart)**
   - 📊 **Sales by Product Line (Bar Chart)**
   - 🏆 **Top Customers by Revenue (Horizontal Bar Chart)**
   - 🌍 **Sales by Region (Choropleth Map)**
   - 🥧 **Order Status Breakdown (Pie Chart)**
✅ **Lightweight and Runs in Any Browser**  
✅ **Downloadable as an HTML File**  

---

## 🔹 Data Structure
The dashboard is generated from a **JSON file**, which follows this structure:

```json
[
    {
        "ORDERNUMBER": 10107,
        "QUANTITYORDERED": 30,
        "PRICEEACH": 95.7,
        "ORDERLINENUMBER": 2,
        "SALES": 2871,
        "ORDERDATE": "2/24/2003 0:00",
        "STATUS": "Shipped",
        "QTR_ID": 1,
        "MONTH_ID": 2,
        "YEAR_ID": 2003,
        "PRODUCTLINE": "Motorcycles",
        "MSRP": 95,
        "PRODUCTCODE": "S10_1678",
        "CUSTOMERNAME": "Land of Toys Inc.",
        "PHONE": 2125557818,
        "ADDRESSLINE1": "897 Long Airport Avenue",
        "CITY": "NYC",
        "STATE": "NY",
        "POSTALCODE": 10022,
        "COUNTRY": "USA",
        "TERRITORY": "NA",
        "CONTACTLASTNAME": "Yu",
        "CONTACTFIRSTNAME": "Kwai",
        "DEALSIZE": "Small"
    }
]
