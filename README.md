# Office Supply Sales
 
Analysis of office product sales, segmented by three marketing methods (Call Only, Email Only, Combination), to determine efficacy. Comparisons examine average and total revenue growth as well as cumulative revenue.

Dataset: Sales over the 6 weeks since product launch

| Column Name       | Details                                                                             |
|-------------------|-------------------------------------------------------------------------------------|
| week              | Numeric, Week sale was made, counted as weeks since product launch                  |
| sales_method      | Character, which of the three sales methods were used for that customer             |
| customer_id       | Character, unique identifier for the customer                                       |
| nb_sold           | Numeric, number of new products sold                                                |
| revenue           | Numeric, revenue from the sales, rounded to 2 decimal places.                       |
| years_as_customer | Numeric, number of years customer has been buying from us (company founded in 1984) |
| nb_site_visits    | Numeric, number of times the customer has visited our website in the last 6 months  |
| state             | Character, location of the customer i.e. where orders are shipped                   |
