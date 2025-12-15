# Digikala-Recommender
# Digikala Hybrid Recommender System

This project presents a **hybrid recommender system** developed using the Digikala dataset. The system is designed to provide personalized product recommendations in two scenarios: when a user visits the website’s landing page and when a user views a specific product.

The recommender combines **Collaborative Filtering** and **Content-Based Filtering** to leverage both user behavior and product content. Collaborative Filtering is implemented using **Singular Value Decomposition (SVD)** to model user–item interactions and predict ratings, while Content-Based Filtering relies on **TF-IDF** and **cosine similarity** to identify similar products based on textual features.

To evaluate the system’s performance, the SVD model is assessed using the **Root Mean Squared Error (RMSE)** metric. The achieved RMSE of approximately **0.453** demonstrates strong predictive accuracy and indicates that the hybrid approach effectively reduces prediction error. Overall, the results show that the proposed system is capable of delivering accurate, relevant, and reliable recommendations, making it suitable for real-world e-commerce applications.

---

## Key Features

* Hybrid recommendation approach (SVD + TF-IDF)
* Personalized landing page recommendations
* Similar product suggestions on product pages
* Algorithm evaluation using RMSE

---

## Technologies

* Python
* Pandas & NumPy
* Scikit-learn
* Singular Value Decomposition (SVD)
* TF-IDF Vectorization
* Cosine Similarity

---

## Application

This project is intended for educational and experimental use and can be extended to large-scale e-commerce recommender systems.

