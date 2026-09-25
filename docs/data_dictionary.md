# Data Dictionary

| Table Name | Purpose |
|------------|---------|
| olist_customers_dataset | Customer information |
| olist_orders_dataset | Order information |
| olist_order_items_dataset | Products purchased in each order |
| olist_products_dataset | Product information |
| olist_order_payments_dataset | Payment details |
| olist_order_reviews_dataset | Customer reviews |
| olist_sellers_dataset | Seller information |
| product_category_name_translation | Category translation |

---

## Key Relationships

customers.customer_id
    ↓
orders.customer_id

orders.order_id
    ↓
order_items.order_id

products.product_id
    ↓
order_items.product_id

orders.order_id
    ↓
payments.order_id