# 🌿 Hybrid Recommendation System for Organic Veda

This project builds a **Hybrid Recommendation System** combining Collaborative Filtering, Content-Based Filtering, and Matrix Factorization to generate personalized product recommendations for customers of Organic Veda – an Ayurvedic and herbal products brand.

---

## 📌 Project Highlights

- Combines **LightFM** (hybrid model) with **Content-Based Filtering** and **User-Product Similarity Scores**.
- Handles **Cold Start** problems via fallback logic.
- Supports **Top-N Ranking**, **Similarity Search**, and **Personalized Recommendations**.
- Designed for scalability using modular pipeline architecture.

---

## 📁 Dataset Information

The dataset includes:

- ✅ Customer purchase history  
- ✅ Product metadata (title, category, description, etc.)  
- ✅ Ratings and interactions  
- ✅ Timestamps

> Dataset: Proprietary or simulated data from **Organic Veda** (or publicly available e-commerce dataset, if specified).

---

## 🧠 Models Used

| Model Type             | Library       | Purpose |
|------------------------|---------------|---------|
| Content-Based Filtering| scikit-learn  | Based on product metadata |
| Collaborative Filtering| LightFM       | User-Item Matrix Factorization |
| Hybrid                 | Custom Logic  | Combine both approaches |
| Popularity Model       | pandas        | Fallback for cold start |
| Neural Net (optional)  | Keras/TensorFlow | Embedding similarity |

---

## ⚙️ How to Run

1. **Install required packages**

```bash
pip install -r requirements.txt
