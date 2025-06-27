# 🔢 Handwritten Digit Recognition with Random Forest


````markdown

This project uses **Random Forest**, a powerful ensemble learning algorithm, to classify handwritten digits from the `sklearn` **Digits Dataset**. The model is trained and tested on pixel-based image data and visualized for better interpretability.

---

## 📊 Dataset

The `load_digits()` dataset from `scikit-learn` includes:
- 1,797 samples of 8x8 grayscale images (64 features each)
- Digits from `0` to `9`
- Pixel values ranging from 0 to 16

---

## 📦 Libraries Used

- `scikit-learn`
- `pandas`
- `matplotlib`
- `numpy`

---

````
## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/digit-classification-rf.git
   cd digit-classification-rf
   ```
2. Open the notebook:

   ```bash
   jupyter notebook Digit-Prediction-Random-Forest.ipynb
   ```

---

## 🧠 Model Used

* **RandomForestClassifier** from `sklearn.ensemble`
* Trained on the 64-pixel features
* Accuracy evaluated using `.score()` and possibly confusion matrix or classification report

---

## 🧪 Evaluation

The model is evaluated using:

* Training/test split (via `train_test_split`)
* Accuracy score
* Optional: Confusion matrix and visualization of predictions

---

## 📈 Visualization

* Displays handwritten digit images
* Shows predictions and ground truth side-by-side
* Visual analysis of model performance

---

## ✅ Result

* High accuracy in classifying handwritten digits
* Demonstrates the efficiency and robustness of Random Forest in classification tasks

---

## 📂 File Structure

```
digit-classification-rf/
│
├── Digit-Prediction-Random-Forest.ipynb   # Main Jupyter notebook
├── README.md                              # Project overview and usage
```

---

## 🤝 Contributing

If you'd like to improve the project or try another classifier (e.g. SVM, kNN), feel free to fork and open a pull request!

---

## 📜 License

[MIT License](LICENSE)

---

