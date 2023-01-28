# Identified problems, business values, and the importance of the problems.
1. Background of the company:
H & M is a multinational clothing company that was founded in 1947. <br>
H&M currently has approximately 4,850 stores and 53 online marketplaces. <br>
The company's online stores offer a wide range of products for customers to look through. However, too many options may make it difficult for customers to find what they are interested in or are looking for, which may prevent them from making a purchase. Because of these concerns, our team have identified the problem below and come up with a solution to help improve and solve these problems.
2. Identified problem:
Problem is to predict what articles each customer will purchase in the 7-day period immediately after the training data ends.
3. Business values and importance of the problem:
Enhancing the shopping experience <br>
Boost product recommendations <br>
Help customers make the right purchase choices → reduce returns → positive implications for sustainability <br>

# Data Description
Articles.csv: detailed metadata for each article_id available for purchase
Article_id (categorical)
Product_code (numeric)
Prod_name: name of products (category: Dragonfly dress, mike tee, Wow printed tee 6.99, 1pk Fun, TP Paddington Sweater) 
Product_type_no: (numeric)
Product_type_name: Types of products (category: trousers, dress, sweater, t-shirt, top)
Product_group_name: Group type of products (category: Garment Upper Body, Garment Lower Body, Garment Full Body, Accessories, Underwear)
Graphical_appearance_no: (numeric)
Graphical_appearance_name: Type of graphical appearance (category: Solid, All over pattern, melange, stripe, denim)
Colour_group_code: Code of color group (numeric)
Colour_group_name: Name of color (category: Black, Dark Blue, White, Light Pink, Grey)

Customers.csv: metadata for each customer_id in dataset
Customer_id (numeric)
FN (numeric)
Active (numeric)
Club_member_status (category: Active, Pre-Create, Other)
Fashion_news_frequency (category: None, Regularly, Other) 
age (numeric)
Postal_code (numeric)

Transactions_train.csv:  the training data, consisting of the purchases each customer for each date, as well as additional information.
T_dat(category: date of the transaction)
Customer_id(numeric: each customer has a unique customer_id num)
Article_id(category: product type)
Price(numeric)
sales_channel_id(category: channel 1 or channel 2)
