#  🌸 Iris-Flower-Classification-using-k-Nearest-Neighbors-k-NN-

## 📖 Project Overview

The Iris dataset contains measurements for 150 iris flowers from three different species:
- Setosa
- Versicolor
- Virginica

Each sample includes:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The objective is to classify the species of the iris flower based on these features using the **k-Nearest Neighbors** algorithm.

---

## 📊 Dataset Source

The dataset is available through:
- `sklearn.datasets.load_iris()`
- Contains 150 samples: 50 from each species
- Features: 4 numerical measurements per sample

---

## 🧪 Exploratory Data Analysis (EDA)

- Shape and summary of the dataset
- Pair plots and scatter matrices to understand class separability
- Correlation heatmap
- Class balance visualization

---

## 🤖 Model: k-Nearest Neighbors (k-NN)

- Algorithm: **k-NN** from `sklearn.neighbors`
- Distance metric: Euclidean
- Tested different values of `k` (odd numbers from 1 to 25)
- Selected the best `k` based on accuracy score

---

## 📈 Evaluation Metrics

- Confusion Matrix
- **Accuracy Score**
- **Classification Report** (Precision, Recall, F1-score)

---

## 📌 Best Performing Model

| Metric | Value |
|--------|-------|
| Best `k` | Depends on experiment, e.g., `k=3` |
| Accuracy | >96% (on test split) |

---

## 💡 Project Highlights

- Explained and visualized the logic of k-NN
- Demonstrated the effect of `k` on bias-variance tradeoff
- Visualized decision boundaries
- Clear breakdown of training vs testing phases

---

## 🚀 Future Enhancements

- Add model persistence (`joblib`)
- Deploy via Streamlit web app for interactive use
- Compare with other classifiers (SVM, Random Forest, Logistic Regression)
- Use grid search for optimized parameter selection

---

## 🛠 Tech Stack

| Library       | Use                         |
|---------------|-----------------------------|
| `scikit-learn`| Machine learning modeling   |
| `pandas`      | Data manipulation           |
| `numpy`       | Numerical operations        |
| `matplotlib`  | Basic plotting              |
| `seaborn`     | Advanced visualization      |
        
---

📚 Lessons Learned

k-NN is simple but powerful for small, well-separated datasets
Importance of choosing the right k and scaling data
Exploratory visualization reveals patterns the model uses
Evaluation is critical: accuracy + confusion matrix = clarity
