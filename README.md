# shopify-supply-chain-simulation
End-to-end Supply Chain Management simulation using Shopify and Excel (ERP style workflow)

# Shopify Supply Chain Management Simulation Project

This project simulates an end-to-end supply chain workflow for an e-commerce product using Shopify as the storefront.

The objective of this project is to demonstrate how supply chain processes work in an ERP-style environment similar to Microsoft Dynamics 365 Supply Chain Management.

The simulation includes supplier sourcing, procurement planning, inventory management, warehouse operations, logistics, demand forecasting, and master planning.

---

# Supply Chain Flow

1. Supplier (China)  
↓  
2. Fulfillment Warehouse (Toronto, Canada)  
↓  
3. Inventory Management (Shopify)  
↓  
4. Customer Orders  
↓  
5. Logistics & Transportation  
↓  
6. Customer Delivery

---

# Tools Used

Shopify – inventory management and order processing  
Excel – demand planning, procurement planning, safety stock calculation  
Logistics evaluation – shipping provider comparison

---

# 1. Supplier Management

Supplier management focuses on identifying and evaluating product suppliers.

Example supplier used in this simulation:

Supplier: Galaxy Lighting Ltd  
Location: Shenzhen, China  
Product: Galaxy Light Projector  
Lead Time: 10 days

Implementation:

Supplier information such as production lead time, supplier location, and product cost were tracked in an Excel supplier planning sheet.

---

# 2. Procurement Management

Procurement management ensures that products are reordered before inventory runs out.

Example reorder rule:

Reorder Threshold = 20 units

When inventory drops below this level, a purchase order should be created.

Implementation:

Inventory levels were monitored using Shopify inventory tracking, and procurement planning was simulated using Excel.

---

# 3. Inventory Management

Inventory management tracks the available quantity of products.

Example inventory structure:

Product: Galaxy Light Projector  
Current Stock: 100  
Reorder Level: 20

Implementation:

Shopify inventory tracking was enabled to monitor stock levels.

Path used:

Shopify Admin → Products → Inventory → Track Quantity

When customers place orders, Shopify automatically decreases inventory.

---

# 4. Warehouse Management

Products are stored in a fulfillment warehouse before shipping to customers.

Example warehouse used in this simulation:

Toronto Fulfillment Warehouse  
Ontario, Canada

Warehouse workflow:

Supplier shipment received  
↓  
Warehouse receives inventory  
↓  
Products stored in warehouse  
↓  
Customer order received  
↓  
Warehouse picks the product  
↓  
Product packed for shipment

Implementation:

Warehouse operations were simulated conceptually based on standard e-commerce fulfillment workflows.

---

# 5. Order Management

Order management handles customer purchases and order processing.

Order workflow:

Customer places order on Shopify store  
↓  
Shopify creates order  
↓  
Inventory automatically decreases  
↓  
Order moves to fulfillment

Implementation:

Shopify's built-in order management system was used to simulate order processing.

---

# 6. Logistics & Transportation Management

Logistics management focuses on delivering products to customers.

Shipping providers used:

Canada Post  
UPS  
FedEx

Example comparison:

Canada Post – 3–7 days  
UPS – 2–5 days  
FedEx – 2–4 days

Implementation:

Shipping providers were compared based on delivery speed and tracking availability.

---

# 7. Demand Planning

Demand planning predicts future product demand.

Example sales data:

January – 50 units  
February – 80 units  
March – 120 units

Implementation:

Historical sales data was analyzed in Excel to estimate demand trends.

---

# 8. Safety Stock Calculation

Safety stock prevents stock shortages.

Formula used:

Safety Stock = Average Daily Sales × Supplier Lead Time

Example:

Average Daily Sales = 4 units  
Supplier Lead Time = 10 days  

Safety Stock = 40 units

Implementation:

Daily demand estimates were multiplied by supplier lead time to determine safety stock.

---

# 9. Lead Time Planning

Lead time represents the total time required to restock products.

Example lead time breakdown:

Supplier production time – 7 days  
International shipping – 8 days  

Total Lead Time = 15 days

---

# 10. Master Planning

Master planning determines how much inventory should be ordered based on demand forecasts and lead time.

Example planning scenario:

Month: April  
Forecast Demand: 150  
Purchase Quantity: 200

Implementation:

Demand forecasting, safety stock levels, and lead time planning were combined to determine procurement quantities.

---

# Project Outcome

This project demonstrates how supply chain processes such as procurement, inventory management, warehouse operations, logistics, and demand planning work together in an e-commerce environment.

The structure of this simulation reflects supply chain modules commonly used in ERP systems such as Microsoft Dynamics 365 Supply Chain Management.

---

# 
Author

Enes Aydogdu
