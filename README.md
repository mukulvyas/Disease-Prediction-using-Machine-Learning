
# 🏥 Disease Prediction System using Machine Learning

This project is a simple **Disease Prediction GUI Application** that allows users to:

* **Register and login**
* **Select symptoms from dropdowns**
* **Predict disease** using one of three machine learning models:

  * Decision Tree
  * Random Forest
  * Naive Bayes

Built using **Python**, **Tkinter**, **Scikit-learn**, and **Pandas**.


## 🛠 Features

* 🔐 **User Authentication**: Simple username-password based login and registration system using local files.
* 🎛️ **Symptom Selection**: Choose up to 5 symptoms from dropdown menus.
* 🧠 **Model Choices**:

  * Decision Tree
  * Random Forest
  * Naive Bayes
* 📊 **Model Accuracy**: Displays prediction with model accuracy.
* 🖼️ **User-friendly GUI** with Tkinter.

---

## 📦 Requirements

Install the required libraries using:

```bash
pip install pandas numpy scikit-learn
```

Tkinter is included with most Python installations.

---

## 🧪 Datasets

* **Training.csv**: Used to train the ML models.
* **Testing.csv**: Used to evaluate model performance.

Each dataset contains:

* Binary symptom indicators as features
* A `prognosis` column representing the disease (target)

---

## 🚀 How to Run

1. Clone the repository or download the files.
2. Make sure `Training.csv`, `Testing.csv`, and `tab.jpg` are in the same directory.
3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook disease_prediction.ipynb
   ```
4. Execute all cells. When the GUI launches:

   * Click **"Start Prediction"**
   * Register or login
   * Select symptoms
   * Click one of the model buttons to get a disease prediction

---

## 🔒 Notes

* User data is stored locally in plain text files (for demo purposes only).
* Ensure the `tab.jpg` image exists in the working directory, or update the image path in code.

---

## 🧠 Algorithms Used

* **Decision Tree Classifier**
* **Random Forest Classifier**
* **Gaussian Naive Bayes**

All models are trained using **scikit-learn** and evaluated with **accuracy score**.



