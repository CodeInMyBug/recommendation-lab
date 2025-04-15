# 🔍 Product Recommendation System

Build a collaborative filtering-based recommendation engine using cosine similarity.
This system identifies similar users based on product ratings and suggests new items based on those shared preferences.

---

## 🧠 Project Summary
- 📊 **Problem**: Recommend products using user similarity
- 🏗️ **Tech Stack**: Python, Pandas, scikit-learn
- 🎯 **Objective**: Suggest products that a user is likely to enjoy based on ratings from similar users

---

## 📁 Files

| File | Description |
|------|-------------|
| `04_product_recommendation.ipynb` | Cosine similarity-based recommender with pivot table and business insights |
| `data/product_recommendation_data.csv` | User-product ratings dataset |

---

## 📊 Dataset Features
- `user_id`: Unique customer ID
- `product_id`: Unique product ID
- `rating`: Rating between 1–5 for interaction strength

---

## 🤖 Recommender Logic
- Create a user-item pivot table with ratings
- Calculate cosine similarity between users
- Recommend top N products not yet rated by the target user, based on ratings from top similar users

---

## ✅ Example Output
```python
recommend("U0001")
# → Returns top 3 recommended product_ids for that user
```

---

## 💡 Business Use Cases
- Personalized product suggestions for users
- Upsell recommendations based on peer behavior
- Cold-start strategies for new users via lookalike matching

---

## 🔮 Next Steps
- Add LightFM or matrix factorization for sparse scalability
- Evaluate recommendation quality using top-N precision/recall metrics

---
