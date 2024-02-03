# Product-Classification-and-Verification
Computer Vision Project to automate tasks such as inventory management, pricing. For example, a retailer could use this technology to automatically identify and classify products in a store, and then use this information to update inventory levels, calculate products prices, and provide with information about the products.

Project Objectives:
1. Apply Image preprocessing or Feature Extraction techniques where needed.
2. Train at least one classification model to determine the product category. You can use Classical computer vision or deep learning. 
3. Train a one/few shot learning model (e.g., Siamese) to verify if a product exists and recognize its type.

Dataset Description:
This dataset Consists of 2 parts for each of the two required tasks(classification & recognition).
1. Product Classification Data: The Dataset for the classification part has 20 different products where each product has training folder and validation folder, the number of training images for each product ranges from (6-11 images), while the number of validation images for each product ranges from (1-3 images).
2. Product Verification/Recognition: The Dataset for the Verification/Recognition part has 60 different products, where each product has number of images ranging from (6-14). Since here the task is one/few shot learning thus the validation folders are totally different from the training folders where the first 40 product are considered the training data, and the remaining 20 products are considered the validation data.
