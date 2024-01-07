# retail_price_optimization
Pricing Analytics with Python

## Overview
    1. what: pricing analytics workbook for finding optimal pricing. In this case would be for retail

## Documentation
    Features (dataframe columns) explanation:
    1. product_id: A unique identifier for each product in the dataset.
    2. product_category_name: The name of the product category to which the product belongs.
    3. month_year: transaction date (dd-mm-yyyy).
    4. qty: The quantity of the product sold or purchased in a given transaction.
    5. total_price: The total price of the product, including any applicable taxes or discounts.
    6. freight_price: The cost of shipping or freight associated with the product.
    7. unit_price: The price of a single unit of the product.
    8. product_name_length: The length of the product name in terms of the number of characters.
    9. product_description_length: The length of the product description in terms of the number of characters.
    10. product_photos_qty: The number of photos available for the product in the dataset.
    11. product_weight_g: The weight of the product in grams.
    12. product_score: A score or rating associated with the product’s quality, popularity, or other relevant factors.
    13. customers: The number of customers who purchased the product in a given transaction.
    14. weekday: number of weekdays in that month of transaction
    15. weekend: number of weekends in that month of transaction.
    16. holiday: number of holidays in that month of transaction.
    17. month: The month in which the transaction occurred.
    18. year: The year in which the transaction occurred.
    19. s: the effect of seasonality
    20. comp_1, comp_2, comp_3: Competitor information or variables related to competitors’ prices, promotions, or other relevant factors.
    21. ps1, ps2, ps3: Product score or rating associated with competitors’ products.
    22. fp1, fp2, fp3: Freight or shipping cost associated with competitors’ products.
    23. volume: unknow???
    24. lag_price: unit price of the previous month

## Acknowledgement 
    Data Source: https://www.kaggle.com/datasets/suddharshan/retail-price-optimization
    Guidline: follow instruction from data science community blog on statso.io by author Aman Kharwal
              link: https://thecleverprogrammer.com/2023/04/17/retail-price-optimization-using-python/
                
## Progress