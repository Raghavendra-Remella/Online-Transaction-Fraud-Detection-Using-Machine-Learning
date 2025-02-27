# **Online Transaction Fraud Detection Using Machine Learning**

A Flask-based web application that detects fraudulent transactions using machine learning models. The application allows users to upload datasets, preprocess data, visualize insights, train machine learning models, and make fraud predictions.

---

## **Features**
- Upload transaction datasets (CSV format).
- Preprocess data (handle categorical values).
- Visualize data with interactive pie charts.
- Train models: Logistic Regression & Decision Tree.
- Evaluate model accuracy.
- Predict fraud based on user input.

---

## **Technologies Used**
- **Backend:** Flask, Pandas, Scikit-Learn
- **Frontend:** HTML, CSS (Jinja Templates)
- **Visualization:** Plotly
- **Machine Learning Models:** Logistic Regression, Decision Tree Classifier

---

## **Installation & Setup**

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### **2. Set Up Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### **3. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4. Run the Application**
```bash
python app.py
```

Application runs at **http://127.0.0.1:5000/**

---

## **Usage**
1. **Upload CSV Dataset** – Upload transaction data.
2. **Preprocess Data** – Convert categorical values.
3. **Visualize Data** – View distribution of transaction types.
4. **Train ML Models** – Train Logistic Regression and Decision Tree models.
5. **Make Predictions** – Input transaction details to predict fraud.

---

## **Folder Structure**
```
Online-Transaction-Fraud-Detection/
│── templates/           # HTML templates (index, result pages)
│── static/              # CSS, JS files (if any)
│── app.py               # Flask application
│── requirements.txt     # Python dependencies
│── README.md            # Project documentation
```

---

## **Contributing**
Feel free to fork this repository and submit pull requests.

---

## **License**
This project is licensed under the MIT License.

