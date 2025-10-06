# E-Commerce Sales Dataset

### Analyzing and Maximizing Online Business Performance

By ANil [source](https://data.world/anilsharma87)

---

### About this dataset

> This dataset provides an in-depth look at the profitability of e-commerce sales. It contains data on a variety of sales channels, including Shiprocket and INCREFF, as well as financial information on related expenses and profits. The columns contain data such as SKU codes, design numbers, stock levels, product categories, sizes and colors. In addition to this we have included the MRPs across multiple stores like Ajio MRP , Amazon MRP  , Amazon FBA MRP , Flipkart MRP , Limeroad MRP  Myntra MRP  and PaytmMRP along with other key parameters like amount paid by customer for the purchase , rate per piece for every individual transaction Also we have added transactional parameters like Date of sale months category fulfilledby B2b Status Qty Currency Gross amt . This is a must-have dataset for anyone trying to uncover the profitability of e-commerce sales in today's marketplace

---

### More Datasets

For more datasets, click [here](https://www.kaggle.com/thedevastator/datasets).

---

### Featured Notebooks

- 🚨 **Your notebook can be here!** 🚨!

---

### How to use the dataset

This dataset provides a comprehensive overview of e-commerce sales data from different channels covering a variety of products. Using this dataset, retailers and digital marketers can measure the performance of their campaigns more accurately and efficiently.

**Steps to maximize the dataset's benefits:**

- Analyze general sales trends by examining info such as month, category, currency, stock level, and customer for each sale. This offers insights into performance per channel.
- Review Shiprocket and INCREFF data to compare profitability via different fulfillment methods for better decision-making.
- Compare prices across channels (Amazon FBA MRP, Myntra MRP, Ajio MRP, etc.) to evaluate margins and quality.
- Examine customer-specific data, including TP 1/TP 2, gross amounts, and rates, to identify performance patterns over time.
- Use overall stock details alongside P&L and yearly expenses to identify cost-saving opportunities such as optimizing delivery options and reducing manual inspections.

---

### Research Ideas

- Analyzing profitability differences between Shiprocket and INCREFF.
- Examining the full cost structure of products, including TP 1 & TP 2, MRP, and platform-based MRP.
- Building machine learning models to predict sales volume and profits, gaining insights into customer preferences and demand variations.

---

### Acknowledgements

If you use this dataset in your research, please credit the original authors.  
[Data Source](https://data.world/anilsharma87)

---

### License

See the dataset description for more information.

---

### Columns

#### File: Cloud Warehouse Comparison Chart.csv

| Column name | Description |
| --- | --- |
| Shiprocket | Data related to profitability via Shiprocket. (Numeric) |
| INCREFF | Data related to profitability via INCREFF. (Numeric) |

---

#### File: Sale Report.csv

| Column name | Description |
| --- | --- |
| SKU Code | Unique product identifier. (String) |
| Design No. | Unique design identifier. (String) |
| Stock | Number of items in stock. (Integer) |
| Category | Product category. (String) |
| Size | Size of the product. (String) |
| Color | Color of the product. (String) |

---

#### File: P & L March 2021.csv

| Column name | Description |
| --- | --- |
| Category | Product type. (String) |
| Sku | Unique product identifier. (String) |
| Catalog | Product category. (String) |
| Weight | Product weight. (Integer) |
| TP 1 | Price on first platform. (Integer) |
| TP 2 | Price on second platform. (Integer) |
| MRP Old | Original product price. (Integer) |
| Final MRP Old | Discounted final price. (Integer) |
| Ajio MRP | Ajio platform price. (Integer) |
| Amazon MRP | Amazon platform price. (Integer) |
| Amazon FBA MRP | Amazon FBA platform price. (Integer) |
| Flipkart MRP | Flipkart platform price. (Integer) |
| Limeroad MRP | Limeroad platform price. (Integer) |
| Myntra MRP | Myntra platform price. (Integer) |
| Paytm MRP | Paytm platform price. (Integer) |
| Snapdeal MRP | Snapdeal platform price. (Integer) |

---

#### File: May-2022.csv

| Column name | Description |
| --- | --- |
| Sku | Unique product ID. (String) |
| Catalog | Product category. (String) |
| Category | Product type. (String) |
| Weight | Product weight. (Integer) |
| MRP Old | Original price. (Integer) |
| Final MRP Old | Discounted final price. (Integer) |
| Ajio MRP | Ajio platform price. (Integer) |
| Amazon MRP | Amazon platform price. (Integer) |
| Amazon FBA MRP | Amazon FBA price. (Integer) |
| Flipkart MRP | Flipkart price. (Integer) |
| Limeroad MRP | Limeroad price. (Integer) |
| Myntra MRP | Myntra price. (Integer) |
| Paytm MRP | Paytm price. (Integer) |
| Snapdeal MRP | Snapdeal price. (Integer) |
| TP 1 & TP 2 MRP Old | Original combined price. (Integer) |

---

#### File: Amazon Sale Report.csv

| Column name | Description |
| --- | --- |
| Category | Product category. (String) |
| Size | Product size. (String) |
| Date | Sale date. (Date) |
| Status | Sale status. (String) |
| Fulfilment | Fulfillment method. (String) |
| Style | Product style. (String) |
| SKU | Stock Keeping Unit. (String) |
| ASIN | Amazon Standard Identification Number. (String) |
| Courier Status | Courier status. (String) |
| Qty | Quantity sold. (Integer) |
| Amount | Sale amount. (Float) |
| B2B | Business-to-business sale. (Boolean) |
| Currency | Sale currency. (String) |

---

#### File: International sale Report.csv

| Column name | Description |
| --- | --- |
| Style | Product style. (String) |
| SKU | Stock Keeping Unit. (String) |
| Size | Product size. (String) |
| DATE | Sale date. (Date) |
| Months | Sale month. (String) |
| CUSTOMER | Customer name. (String) |
| PCS | Quantity sold. (Integer) |
| RATE | Price per piece. (Float) |
| GROSS AMT | Total sale amount. (Float) |

---

#### File: Expense IIGF.csv

| Column name | Description |
| --- | --- |
| Recived Amount | Total received from sales. (Numeric) |

---

### Acknowledgements

If you use this dataset in your research, please credit the original authors.  
[ANil](https://data.world/anilsharma87)
