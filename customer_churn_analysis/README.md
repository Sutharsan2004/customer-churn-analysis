# 📊 Customer Churn Analysis for Telecom Industry

This project aims to predict telecom customer churn using machine learning and generate actionable insights to improve customer retention. The dataset includes customer demographics, service usage, and account information.

---

## 📁 Project Structure

```
customer_churn_analysis/
├── data/
│   └── telco_churn.csv              # Input dataset (not uploaded to GitHub)
├── notebooks/
│   └── churn_analysis.ipynb         # Main Jupyter Notebook with code
├── outputs/
│   └── churn_segments.csv           # Model predictions with segmentation
├── requirements.txt                 # Project dependencies
└── README.md                        # Project documentation
```

---

## 📌 Problem Statement

In the highly competitive telecom sector, customer churn leads to revenue loss. This project uses machine learning to predict churn and segment users based on risk, enabling targeted retention strategies.

---

## 🧰 Tools & Technologies

- Python, Jupyter Notebook
- Pandas, NumPy, Scikit-learn
- ELI5 (Model explainability)
- Matplotlib (Visualization)

---

## ⚙️ How to Run This Project

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/customer-churn-analysis.git
   cd customer-churn-analysis
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Add your dataset file as:
   ```
   /data/telco_churn.csv
   ```

4. Launch the notebook:
   ```bash
   jupyter notebook notebooks/churn_analysis.ipynb
   ```

5. Run cells to train the model and generate outputs.

---

## 💡 Key Features

- Data cleaning and preprocessing
- Label encoding of categorical features
- Random Forest model for churn prediction
- ELI5-based model explainability
- Customer segmentation:
  - At Risk
  - Loyal
  - Dormant
- Exportable churn prediction results

---

## 📤 Output Files

- `outputs/churn_segments.csv`: Final data with churn probabilities and segments
- Segment distribution chart
- ELI5 top features chart

---

## ✅ Business Recommendations

- Provide offers or discounts to "At Risk" users
- Reward "Loyal" customers with exclusive benefits
- Reconnect with "Dormant" users using personalized messages

---

## 📬 Contact

For queries or feedback, please reach out to the project contributor.

> ⚠️ Note: Raw dataset is excluded from GitHub. Please manually place it inside the `/data` folder.
