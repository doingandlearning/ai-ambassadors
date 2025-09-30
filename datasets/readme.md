### Dataset 1: Customer Service Logs

* **Rows:** 1,200
* **Columns:** 5
* **Contains:** 
  - `ticket_id`: Unique identifier for each support ticket
  - `created_at`: When the ticket was first created
  - `resolved_at`: When the ticket was closed/resolved
  - `channel`: Communication method (email, phone, chat, etc.)
  - `category`: Type of issue (billing, technical, general, etc.)
  - `escalated`: Whether the ticket required escalation (true/false)
  - `first_contact_resolution`: Whether resolved on first contact (true/false)
  - `resolution_minutes`: Time taken to resolve in minutes
  - `satisfaction`: Customer satisfaction rating (1-5 scale)
  - `sentiment`: Overall sentiment of the interaction (positive, neutral, negative)
* **Context:** Represents customer interactions and outcomes.

---

### Dataset 2: Delivery Times

* **Rows:** 800
* **Columns:** 6
* **Contains:** 
  - `order_id`: Unique identifier for each order
  - `ship_date`: Date the order was shipped
  - `deliver_date`: Date the order was delivered
  - `region`: Geographic region of delivery
  - `courier`: Shipping company used
  - `delivery_days`: Number of days from ship to delivery
  - `weight_kg`: Weight of the package in kilograms
  - `bulky_item`: Whether the item is considered bulky (true/false)
* **Context:** Covers fulfilment and shipping performance.

---

### Dataset 3: Marketplace Trends

* **Rows:** 600
* **Columns:** 7
* **Contains:** 
  - `date`: Date of the data snapshot
  - `category`: Product category (electronics, clothing, home, etc.)
  - `listings`: Number of active product listings
  - `sales`: Number of items sold
  - `gmv`: Gross Merchandise Value (total sales revenue)
* **Context:** Provides a snapshot of supply and demand across categories.

---

### Dataset 4: Search Conversion Funnel

* **Rows:** 900
* **Columns:** 9
* **Contains:** 
  - `month`: Month of the data
  - `product_id`: Unique identifier for each product
  - `device`: Device type used (mobile, desktop, tablet)
  - `impressions`: Number of times product appeared in search results
  - `clicks`: Number of times product was clicked
  - `add_to_cart`: Number of times product was added to cart
  - `conversions`: Number of completed purchases
  - `revenue`: Total revenue generated
  - `price_band`: Price range category (budget, mid-range, premium)
* **Context:** Shows how customers move from search → purchase.


