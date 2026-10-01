Data Analysis has been done using Excel.
Main excel features used:
1. Power Query
2. Tables
3. Pivot Tables
4. Power Pivot
5. Basic DAX measures
6. Charts, Slicers, Dashboard

Dataset downloaded from Maven Analytics website

Raw dataset file contains the following coloumns:
1. transaction_id
2. transaction_date
3. transaction_time
4. transaction_qty
5. store_id
6. store_location
7. product_id
8. unit_price
9. product_category
10. product_type
11. product_detail


After loading data, cleaning and transforming it using power query editor, following new columns are added:
1. order_month (extracted from transaction_date)
2. order_day (e.g monday, extracted from transaction_date)
3. order_hour (extracted from transaction_time)
4. total_amount (extracted by multiplying unit_price with transaction_qty)
5. product_size (extracted from product_detail)
6. Day of Week (e.g 1,2  extracted from transaction_date)
6. Month (e.g 1,2,10,12  extracted from transaction_date)


Following questions are answered via Pivot Tables, Dashboard and Pivot Charts and Slicers

1. Total Sales (Revenue).
2. Total Footfall.
3. Average Bill (revenue) per person.
4. Average order (quantity) per person.
5. Quantity ordered based on hours.
6. % of Revenue by Category.
7. % of Size Distribution based on orders.
8. Footfall & Sales over various store locations.
9. Top 5 product sales wise.
10. Number of orders based on weekdays.