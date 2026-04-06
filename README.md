## Instagram-Thrift-Store-ERD

### sellers
Represents people or businesses who list and sell products on the platform.

### customers
Users who browse, purchase, and interact with products.

### addresses
Stores location details used for deliveries.

### customer_addresses
Links customers to one or more addresses (home, office, etc.).

### products
High-level product listings created by sellers (e.g., “T-shirt”).

### product_variants
Specific versions of a product (e.g., size M, color red).

### variants_inventory
Tracks available stock for each product variant.

### orders
Represents a purchase made by a customer.

### order_items
Individual items within an order, including quantity and price at purchase time.

### payments
Stores payment transactions related to orders.

### shipments
Handles delivery details, tracking, and shipping status for orders.
