# Recommendation_system
# 📊 CODTECH Internship - Task 4

## 🧠 Recommendation System using Matrix Factorization (SVD)

This project is part of the CODTECH Internship Program (Task-4), which focuses on building a **Recommendation System** using collaborative filtering techniques, specifically **Matrix Factorization (SVD)**.

---

## 🚀 Objective

To develop a recommendation engine that suggests items (movies) to users based on past user-item interactions, using the **Surprise** library.

---

## 📁 Dataset

- **Name**: MovieLens 100k  
- **Source**: Built-in dataset from the `Surprise` Python library  
- **Description**: Contains 100,000 ratings from 943 users on 1,682 movies.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- scikit-surprise

---

## 📌 Methodology

1. **Data Loading**: MovieLens 100k dataset via `Dataset.load_builtin()`
2. **Model**: Matrix Factorization using `SVD` from the Surprise library
3. **Train/Test Split**: 80% training, 20% testing
4. **Evaluation Metrics**:  
   - RMSE (Root Mean Squared Error)  
   - MAE (Mean Absolute Error)
5. **Top-N Recommendation**: Generates top N movie recommendations for a given user.

---

## 📊 Results

- RMSE and MAE were computed on the test dataset.
- Sample prediction for a specific user and item was demonstrated.
- Top-5 movie recommendations for a selected user were displayed.

---

## 📌 How to Run

1. Open the notebook `Recommendation_system.ipynb` in Google Colab.
2. Run all cells from top to bottom.
3. Ensure you have internet access to install dependencies.

---

## ✅ Task Outcome

- [x] Built using Collaborative Filtering (SVD)
- [x] Implemented using Surprise Library
- [x] Model Trained and Evaluated
- [x] Predictions and Top-N Recommendations Completed

---

## 🏁 Completion

✅ This project completes Task-4 of the CODTECH Internship.  
🎓 A certificate will be issued upon internship completion.

---
