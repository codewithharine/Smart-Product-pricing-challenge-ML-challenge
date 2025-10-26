# Smart-Product-pricing-challenge-ML-challenge
Predicting optimal e-commerce product prices using textual features and LightGBM regression.

**Team Nxtgen**  
Harine K. S | Dharshini S | Bhavishya Priyadarshini V | Aboorva J  

## 🧩 Problem Overview
Predict optimal product prices for an e-commerce dataset using product text and image links.  

## 🧠 Approach
- Text cleaning & preprocessing (`catalog_content`)
- TF-IDF feature extraction (top 10k features)
- LightGBM Regressor for price prediction  
- Validation using RMSE & SMAPE  

## ⚙️ Model Details
- `num_leaves=64`, `learning_rate=0.05`, `n_estimators=2000`
- Validation RMSE ≈ 0.68  

## 📈 Results
- Stable SMAPE on validation set  
- IPQ and descriptive keywords improved prediction accuracy  

## 🚀 Future Work
- Incorporate image embeddings (ResNet/EfficientNet)
- Multimodal model combining text and image features  

## ⚖️ Compliance
No external data or price lookup used — trained only on provided dataset.

This project demonstrates our ability to handle real-world ML pipelines, text analytics, and ethical modeling in e-commerce pricing.
