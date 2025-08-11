# Spam Message Classifier (Internship Project)

This project is a part of my internship task under **Elite Tech Intern**.  
The goal was to implement a **Machine Learning model using scikit-learn** to classify messages as **Spam** or **Ham (Not Spam)**.

## 🔍 Problem Statement

Create a predictive model that classifies messages as either spam or not spam using natural language processing and machine learning techniques.  
The model should be able to take a text message input and accurately predict whether it's spam.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `Spam_Classifier_Project.ipynb` | Jupyter notebook containing the code and model implementation |
| `spam.csv` | Dataset used for training and testing the spam classifier |
| `requirements.txt` | Python libraries required to run the notebook |
| `README.md` | Project overview and setup instructions |

---

## 📊 Dataset Info

- The dataset used is based on the [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) which contains 5,572 messages labeled as either:
  - `spam`: Unwanted promotional or malicious messages
  - `ham`: Normal (non-spam) messages

---

## 📌 Technologies Used

- Python 🐍
- Pandas
- scikit-learn
- Jupyter Notebook (via VS Code)

---

## ⚙️ How the Model Works

1. **Load the dataset** using pandas.
2. **Preprocess** the text (cleaning, vectorization using CountVectorizer).
3. **Split** the data into training and testing sets.
4. **Train** a machine learning model (Multinomial Naive Bayes).
5. **Evaluate** the model with accuracy and classification report.
6. **Test** with a custom message to check prediction.

---

## 🧪 Sample Output

Accuracy: 98.56%

Classification Report:
precision recall f1-score support
0 0.99 0.99 0.99 966
1 0.94 0.95 0.95 149

yaml
Copy
Edit

---

## ▶️ How to Run

1. Clone or download this project folder.
2. Open it in **VS Code**.
3. Install dependencies:

```bash
pip install -r requirements.txt
Run the notebook:

Use Jupyter notebook inside VS Code, OR

Run in terminal using:

bash
Copy
Edit
jupyter notebook Spam_Classifier_Project.ipynb
🎓 Submitted By
Name: piyush Chaudhary 
Internship Program: Elite Tech Intern
Task: Task 4 – Machine Learning Model Implementation