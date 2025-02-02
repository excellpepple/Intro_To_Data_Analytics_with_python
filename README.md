# 📊 Sales Data Analysis - Programming Assignment 1  

## 🏆 Objective  
This project focuses on **data analytics using Python** to analyze sales data from an online business. Through this assignment, key programming concepts are practiced, including:  
- ✅ Functions & Argument Passing  
- ✅ List Comprehensions  
- ✅ Lambda Functions  
- ✅ Filtering Operations  
- ✅ Higher-Order Functions  

## 📁 Dataset Overview  
The dataset (`sale_data.csv`) contains **100 rows** of sales transactions, with the following **7 fields**:  

1. **Order ID** – Unique sequence number (1-100).  
2. **Category ID** – Product category (1-6).  
3. **Unit Price** – Price per unit (two decimal places).  
4. **Quantity** – Number of items sold per transaction.  
5. **Payment Method** – (Credit Card = 1, Digital Wallet = 2).  
6. **Customer Age**  
7. **Customer Gender** – (Female = 1, Male = 2).  

---

## 📌 Features & Implementation  

### ✅ **Task 1: Loading Data**  
- `read_data(file_name)`: Reads the sales data into lists.  
- `print_head(lists)`: Displays the first **5 rows** in a formatted way.  

### ✅ **Task 2: Calculating Key Sales Metrics**  
- `key_metrics(lists)`: Computes:  
  - **Total Sales Revenue**  
  - **Average Cost per Order**  

### ✅ **Task 3: Filtering High-Value Items**  
- **Filters** and prints orders where **Unit Price > $30**.  

### ✅ **Task 4: Gender-Based Order Analysis**  
- `gender_based_order(gender_list)`: Computes the **total number of orders** by **gender**.  

### ✅ **Task 5: Payment Method Ratio**  
- `payment_ratio(payment_method)`: Uses a **lambda function** to calculate the **percentage of each payment method**.  

### ✅ **Task 6: Orders by Category**  
- `analyze_category(price, quantity, category_id)`:  
  - Computes **number of orders** and **total revenue per category**.  
  - Identifies **the most purchased item category**.  
  - Saves the results to `category_analysis.txt`.  

### ✅ **Task 7: Function Objects & Higher-Order Functions**  
- Implements functions to compute **max, min, and average values**.  
- `run_funcs(list, func_array)`: A **higher-order function** that applies multiple function objects.  

---

## 🚀 Usage  

### 🔧 **Run the Project**
Ensure you have Python installed, then execute the scripts in a **Jupyter Notebook** or a standard Python environment.  

```python
# Example Usage:
data = read_data("sale_data.csv")
print_head(data)
key_metrics(data)
