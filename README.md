# Shopify-Sales-DashBoard_Power-BI

# 📊 Shopify Sales Analysis – Power BI Dashboard

This Power BI project analyzes Shopify sales data to understand sales trends, customer purchase behavior, and payment patterns, helping businesses make data-driven decisions.

Shopify is an online e-commerce platform that allows individuals and businesses to create and manage online stores without technical skills.

• Dataset was already cleaned, so no data cleaning was required  
• Used Shopify Customer & Sales dataset containing order, customer, product, location, pricing, tax, and payment details  
• Dashboard background color used: **#2A313B** for a modern dark theme  
• Inserted custom shapes and text boxes to design the dashboard layout  

• Created key measures for transaction performance:
  - Net Sales = SUM(Subtotal Price)
  - Total Quantity = SUM(Quantity)
  - Net Average Order Value = AVERAGE(Subtotal Price)

• Displayed these KPIs using formatted card visuals  

• Created customer purchase behavior measures:
  - Total Customers = DISTINCTCOUNT(Customer ID)
  - Single Order Customers = customers with exactly one order
  - Repeat Customers = customers with more than one order

• Created retention and value KPIs:
  - Lifetime Value (LTV) = Net Sales / Total Customers
  - Repeat Rate = Repeat Customers / Total Customers
  - Purchase Frequency = Total Orders / Total Customers

• Built multiple interactive visuals:
  - Shape Map with parameter-based slicer
  - Map visual using a custom location measure combining City, Province, and Country
  - Clustered bar chart showing city-wise net sales
  - Area chart showing day-wise net sales (March data)
  - Stacked column chart for hour-wise net sales (Hour extracted from Invoice Date)
  - Donut chart showing Gateway (payment method) usage
  - Stacked column chart showing Net Sales by Product Type

• Created a calculated column to extract hour:
  - Hour = HOUR(Invoice Date)

• Implemented dynamic chart titles using a parameter table and DAX logic  
• Added Shopify logo for branding  
• Included slicers for filtering and page navigation for detailed analysis  

Tools Used: Power BI, DAX, Power Query  

This dashboard provides clear insights into sales performance, customer retention, payment behavior, and product trends, and is suitable for business reporting, portfolio projects, and interview discussions.
