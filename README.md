<a name="readme-top"></a>

# Amazon_Sales_Analytics
Explore actionable insights into Amazon sales and Prime Video performance with these Power BI dashboards. 

## Table of Contents
- [About Data Set](#about-data-set)
- [Project Description](#project-description)
- [Author](#author)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## About Data Set
# Dataset Description

## Overview
This dataset contains information about various orders made on Amazon.in during April 30, 2022. The dataset includes details such as Order ID, Date, Status, Fulfilment method, Sales Channel, Ship Service Level, Style, Category, Courier Status, Quantity, Currency, Amount, Ship City, Promotion IDs, B2B (Business-to-Business), and whether the order was fulfilled by a third-party.

## Dataset Columns
1. **Order ID:** A unique identifier for each order.
2. **Date:** The date when the order was processed.
3. **Status:** The order status, which can be "Shipped," "Cancelled," "Shipped - Delivered to Buyer," or "Shipped - Delivered to Buyer."
4. **Fulfilment:** Indicates whether the order was fulfilled by a Merchant or Amazon.
5. **Sales Channel:** The sales channel through which the order was made, in this case, "Amazon.in."
6. **Ship Service Level:** The shipping service level used for the order, which can be "Standard" or "Expedited."
7. **Style:** The style of the product ordered.
8. **Category:** The category of the product ordered.
9. **Courier Status:** The status of the courier delivering the order, e.g., "Shipped."
10. **Quantity:** The quantity of items ordered.
11. **Currency:** The currency used for the transaction, here "INR" (Indian Rupees).
12. **Amount:** The total amount for the order in INR.
13. **Ship City:** The city where the order is being shipped to.
14. **Promotion IDs:** IDs of any promotions or discounts applied to the order.
15. **B2B (Business-to-Business):** Indicates whether the order is a B2B transaction, with "TRUE" or "FALSE."
16. **Fulfilled by:** Information about who fulfilled the order, whether Amazon or a third-party seller.
17. **ship-service-level:** The ship-service-level of the order.

## Sample Rows
Here are a few sample rows from the dataset:
| ID | Date | Status | Fulfilment | Sales Channel | Ship Service Level | Style | Category | Courier Status | Quantity | Currency | Amount | Ship City | Promotion IDs | B2B | Fulfilled by |
|----|------|--------|------------|---------------|---------------------|-------|----------|----------------|----------|----------|--------|-----------|---------------|-----|--------------|
| 405-8078784-5731545 | 04-30-22 | Cancelled | Merchant | Amazon.in | Standard | SET389 | Set | | 0 | INR | 647.62 | MUMBAI | | FALSE | Easy Ship |
| 171-9198151-1101146 | 04-30-22 | Shipped - Delivered to Buyer | Merchant | Amazon.in | Standard | JNE3781 | kurta | Shipped | 1 | INR | 406 | BENGALURU | Multiple promotion IDs | FALSE | Easy Ship |
| 404-0687676-7273146 | 04-30-22 | Shipped | Amazon | Amazon.in | Expedited | JNE3371 | kurta | Shipped | 1 | INR | 329 | NAVI MUMBAI | IN Core Free Shipping 2015/04/08 23-48-5-108 | TRUE | |
| 403-9615377-8133951 | 04-30-22 | Cancelled | Merchant | Amazon.in | Standard | J0341 | Western Dress | | 0 | INR | 753.33 | PUDUCHERRY | | FALSE | Easy Ship |
| 407-1069790-7240320 | 04-30-22 | Shipped | Amazon | Amazon.in | Expedited | JNE3671 | Top | Shipped | 1 | INR | 574 | CHENNAI | | FALSE | |
| 404-1490984-4578765 | 04-30-22 | Shipped | Amazon | Amazon.in | Expedited | SET264 | Set | Shipped | 1 | INR | 824 | GHAZIABAD | IN Core Free Shipping 2015/04/08 23-48-5-108 | FALSE | |
| 408-5748499-6859555 | 04-30-22 | Shipped | Amazon | Amazon.in | Expedited | J0095 | Set | Shipped | 1 | INR | 653 | CHANDIGARH | IN Core Free Shipping 2015/04/08 23-48-5-108 | FALSE | |
| 406-7807733-3785945 | 04-30-22 | Shipped - Delivered to Buyer | Merchant | Amazon.in | Standard | JNE3405 | kurta | Shipped | 1 | INR | 399 | HYDERABAD | Multiple promotion IDs | FALSE | Easy Ship |
| 407-5443024-5233168 | 04-30-22 | Cancelled | Amazon | Amazon.in | Expedited | SET200 | Set | Cancelled | 0 | | | HYDERABAD | IN Core Free Shipping 2015/04/08 23-48-5-108 | FALSE | |
| 402-4393761-0311520 | 04-30-22 | Shipped | Amazon | Amazon.in | Expedited | JNE3461 | kurta | Shipped | 1 | INR | 363 | Chennai | | FALSE | |
| 407-5633625-6970741 | 04-30-22 | Shipped | Amazon | Amazon.in | Expedited | JNE3160 | kurta | Shipped | 1 | INR | 685 | CHENNAI | | FALSE | |
| 171-4638481-6326716 | 04-30-22 | Shipped | Amazon | Amazon.in | Expedited | JNE3500 | kurta | Shipped | 1 | INR | 364 | NOIDA | | FALSE | |
| 405-5513694-8146768 | 04-30-22 | Shipped - Delivered to Buyer | Merchant | Amazon.in | Standard | JNE3405 | kurta | Shipped | 1 | INR | 399 | Amravati | Multiple promotion IDs | FALSE | Easy Ship |
| 408-7955685-3083534 | 04-30-22 | Shipped | Amazon | Amazon.in | Expedited | SET182 | Set | Shipped | 1 | INR | 657 | MUMBAI | | FALSE | |
| 408-1298370-1920302 | 04-30-22 | Shipped - Delivered to Buyer | Merchant | Amazon.in | Standard | J0351 | Set | Shipped | 1 | INR | 771 | MUMBAI | Multiple promotion IDs | FALSE | |
| 403-4965581-9520319 | 04-30-22 | Shipped - Delivered to Buyer | Merchant | Amazon.in | Standard | PJNE3368 | kurta | Shipped | 1 | INR | 544 | GUNTAKAL | Multiple promotion IDs | FALSE | Easy Ship |



## Usage
This dataset can be used for various analytical and business purposes, such as understanding order patterns, tracking order statuses, evaluating sales channels, and assessing fulfilment methods. It can also be used to analyze the impact of promotions on sales and to identify trends in B2B transactions.

Please note that this is a sample dataset with a limited number of entries. For more comprehensive analysis, additional data may be required.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Project Description
In this project, I have visualized data trends and analyzed key metrics to optimize business strategies for Amazon.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Author
 @[Abbas S.](https://github.com/clkride)

## License
The MIT License (MIT)

Copyright (c) 2023 Abbas Singapurwala

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Acknowledgments

<p align="right">(<a href="#readme-top">back to top</a>)</p>

