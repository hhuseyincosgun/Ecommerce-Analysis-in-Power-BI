# Ecommerce-Analysis-in-Power-BI
 In this Power BI project, we'll look at a real online store's data to find out useful things for a *pet supply company* called Whiskique.

### Metadata

We will be using a fictitious data source for product sales. The data is located in **four CSV files**. The sales table is the primary transaction table. The product and customer tables contain additional attributes. The state mapping has consistent values for locations. We will be creating relationships between the tables during our data preparation steps.


#### Sales Table
| Column             | Description                                                            |
| -------------------| ---------------------------------------------------------------------- |
| Transaction Date   | Date of purchase                                                       |
| Customer ID        | Customer identifier                                                    |
| Description        | Product description                                                    |
| Stock Code         | Product code                                                           |
| Invoice No         | An invoice contains multiple products and represents a single checkout |
| Quantity           | Quantity of a product purchased                                        |
| Sales              | Total amount of a product in a single checkout                         |
| Unit Price         | Unit price of a product                                                |

#### Product Table
| Column                  | Description                                        |
| ------------------------| -------------------------------------------------- |
| Stock Code              | Product code                                       |
| Weight                  | Weight of a single unit                            |
| Landed Cost             | Manufacturer cost + freight                        |
| Shipping_Cost_1000_m    | Average cost of shipping 1000 miles to customers   |
| Description             | Most recent product description                    |
| Category                | Product category                                   |

#### State mapping
| Column               | Description                                      |
| -------------------- | ------------------------------------------------ |
| Order State          | State code, description and all its variations   |
| State                | The full name of the state                       |
| Region               | Region name                                      |
| State Abbreviation   | A standardized state code                        |

#### Customer table
| Column         | Description                      |
| -------------- | -------------------------------- |
| Customer ID    | Customer unique identifier       |
| Order City     | City                             |
| Order Postal   | Postal code                      |
| Order State    | State                            |
| Latitude       | Latitude of customer location    |
| Longitude      | Longitude of customer location   |

-------
Let's examine a clear example showing the overall expenses involved in the supply chain stages of canned pet food. In this instance, out of a $20 purchase of canned pet food, $4 is allocated to the manufacturer, also known as the cost of goods sold (COGS). Additionally, $1.50 is utilized for freight and fulfillment costs, covering shipping from the manufacturer to the warehouse and warehouse storage fees. The last step, delivering the product to customers, incurs a $5 charge. This leaves an $8 profit margin before administrative expenses.

![Supply Chain](https://github.com/hhuseyincosgun/Ecommerce-Analysis-in-Power-BI/assets/21257660/586014ec-c497-4b49-9d51-ed02a60b7e61)

### Whiskique's business goals

Primary Bussiness Golas:
- Serve as many customers as possible and increase sales
- Reduce operating costs

Through the analysis work we will carry out for Whiskique, we will advise on increasing sales and reducing expenses.

### Increase sales
- Cross-sell: Promote a relevant product at point of purchase
- Upsell: Promote a higher priced alternative or a higher quantity of a product.

For example, when a customer is ready to buy a beach umbrella, present an offer on beach chairs. In an upsell, you promote a higher-priced alternative or a higher quantity of a product. For example, when a customer buys pet food regularly, present an offer on organic food.

### Shipping cost reduction strategies
For shipping cost reductions, we can explore some of the following alternatives.
- Shipment consolidation
- Package dimension or weight
- Ship higher quantity

### Market basket analysis

- Find products frequently bought together
- Determine correlation coefficient between purchased items
  - Implemented as a correlation matrix
























  
