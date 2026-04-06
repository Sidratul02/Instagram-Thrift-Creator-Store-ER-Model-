 ## Instagram Thrift & Handmade Store – ER Diagram

This project presents an ER diagram for an Instagram-based business selling thrifted (unique) and handmade (multi-unit) products. It models key entities like Products, Customers, Orders, Order Items, Payments, Shipping, and Inventory.

The design supports real-world scenarios such as one customer placing multiple orders, orders containing multiple products, and handling both single-piece and batch inventory. Proper PKs, FKs, and relationships ensure data integrity, clarity, and scalability.

##  Objectives  
- Manage unique thrift items and multi-unit handmade products  
- Track inventory and product attributes (size, color, condition, price)  
- Handle customer orders and order history  
- Maintain payment and shipping status  

##  Entities  
- Customer  
- Product  
- Order  
- Order_Item (Junction Table)  
- Payment  
- Shipping  
- Inventory  

## Relationships  
- One Customer → Many Orders  
- One Order → Many Products (via Order_Item)  
- Products categorized as Thrift (single unit) or Handmade (multiple units)  
- Each Order → One Payment & One Shipping record  

##  Keys & Constraints  
- Primary Keys (PKs) defined for all entities  
- Foreign Keys (FKs) used to maintain relationships  
- Many-to-many relation resolved using Order_Item  

##  Design Features  
- Normalized and clean structure  
- Scalable for business growth  
- Reflects real-world use cases  
- Easy to understand and implement  
