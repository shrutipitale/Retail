# Retail
Transactional Retail Dataset of Electronics Store

This dataset contains information about an online electronic store. The store has three warehouses from which goods are delivered to customers. The goal of this EDA is to analyze warehouse efficiency, order price, and customer satisfaction.

Goals of EDA
Warehouse Efficiency: Evaluate the performance of each warehouse in terms of delivery times and order fulfillment efficiency.

Order Price: Analyze the distribution of order prices, seasonal trends, and the impact of various factors on the final order price.

Customer Satisfaction: Assess customer satisfaction through ratings and reviews, and identify factors that influence customer happiness.

This dataset includes the following information:
- **order_id**: Unique identifier for each order.
- **customer_id**: Unique identifier for each customer.
- **date**: Date when the order was placed.
- **nearest_warehouse**: ID of the warehouse closest to the customer.
- **shopping_cart**: List of items in the customer's shopping cart.
- **order_price**: Total price of items in the order before any discounts or delivery charges.
- **delivery_charges**: Additional charges for delivering the order.
- **customer_lat**: Latitude of the customer's location.
- **customer_long**: Longitude of the customer's location.
- **coupon_discount**: Discount applied to the order using a coupon.
- **order_total**: Final amount paid by the customer after discounts and delivery charges.
- **season**: Season during which the order was placed (e.g., Winter, Spring, Summer, Fall).
- **is_expedited_delivery**: Indicates if the order was expedited for faster delivery (1 for expedited, 0 for standard).
- **distance_to_nearest_warehouse**: Distance from the customer's location to the nearest warehouse.
- **latest_customer_review**: Text of the latest review provided by the customer.
- **is_happy_customer**: Binary indicator of whether the customer was happy with the order (1 for happy, 0 for unhappy).


