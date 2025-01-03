# Cosmetics-Ingredient-Analysis-and-Content-Based-Recommendation-System-main

Project Description: Cosmetics Ingredient Analysis and Content-Based Recommendation System

The Cosmetics Ingredient Analysis and Content-Based Recommendation System is designed to help consumers, particularly those with sensitive or specific skin needs, make informed choices when selecting cosmetic products. By focusing on each product’s ingredient list, our system automatically identifies similarities and clusters items that share significant ingredient overlap.

Leveraging a dataset of approximately 1,472 products (e.g., sourced from Sephora), we first filter and inspect the data to isolate relevant subsets, such as moisturizers suitable for dry skin. We then tokenize ingredient lists, normalize text, and convert these tokens into a one-hot encoded vector, creating a high-dimensional representation of each product’s formulation. To address the difficulty of visualizing hundreds or thousands of possible ingredients, we apply t-SNE (t-distributed Stochastic Neighbor Embedding), which compresses these high-dimensional vectors into two dimensions.

This dimensionality reduction reveals clusters of products with comparable ingredients, and we use Bokeh to build an interactive scatter plot where each point corresponds to a cosmetic item. Hovering over a point displays its brand, name, price, and rank, allowing for quick, intuitive exploration of potential alternatives or substitutes. Finally, by comparing ingredient lists of nearby points, users can identify products that may offer similar benefits or avoid specific ingredients known to cause irritation.

Overall, this project demonstrates a robust, content-based strategy for skincare recommendations, highlighting how data science techniques can simplify the often overwhelming task of choosing suitable cosmetic products.
