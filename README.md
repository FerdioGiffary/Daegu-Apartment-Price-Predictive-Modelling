# Daegu Apartment Price Predictive Modelling
This project develops a machine learning model to predict apartment sale prices in Daegu, South Korea, using internal source data.
The goal is to support real estate agents in setting accurate, consistent, and data-driven property prices.

#### Business Objectives:
- Identify the key factors that influence apartment prices in Daegu.
- Build a predictive model with high accuracy (MAPE < 20%).
- Provide fast, reliable price estimates to help agents improve decision-making.
- Reduce pricing errors, negotiation time, and inconsistent valuations.

## 2. Data Sources
- [Daegu Apartment Dataset] – Contains 4,123 apartment records with features such as hallway type, building facilities, subway accessibility, unit size, and sale price.
(*Dataset is stored locally due to licensing*)

## 3. Technologies Used
- Programming Language: Python (Pandas, NumPy, SciPy)
- Machine Learning: scikit-learn, XGBoost
- Visualization: Matplotlib, Seaborn
- Version Control: GitHub
- Development Environment: Jupyter Notebook, Visual Studio Code

## 4. Project Structure

```
├── README.md                      <- Project documentation (you are here)
│
├── data
│   ├── data_daegu_apartment.csv  <- Internal Sources
│
├── models/                       <- Serialized machine learning models (.pkl)
│
├── notebooks
│   ├── main.ipynb
│
└── reports
│   ├── videos.txt               <- Link to gdrive for video presentation
│   ├── slides.txt               <- Link to canva for business presentation
│
└── requirements.txt             <- Python package list
```

## 5. Summary of Finding
### 5.1 Business Insight
- Apartment size, hallway type, in-building facilities, and year built strongly influence sale prices.
- Internal features matter more than external features like subway distance.
- Data-driven pricing improves listing accuracy and client trust.

### 5.2 Actionable Recommendation
- Use the model’s price predictions as a *baseline* when advising clients.
- Highlight high-value features (terraced hallway, newer building, larger size) in marketing materials.
- Combine model predictions with your market knowledge to set final listing prices

## 6. Contact
- Name     : Ferdio Giffary
- Email    : ferdiogiffary@gmail.com
- Linkedin : linkedin.com/in/ferdiogiffary/



