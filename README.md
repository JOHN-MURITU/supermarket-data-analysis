# 🛒 Supermarket Sales Analysis — Data-Driven Insights for Retail Growth

## 📖 Overview
This project analyzes sales data from a supermarket chain to uncover key patterns in **branch performance**, **customer segmentation**, **product line performance**, and **revenue volatility**.  

The analysis demonstrates how **data analytics can transform operational data into strategic business insight** — and is contextualized for **Kenyan retail environments** like **Naivas** and **Mathai Supermarket**.

---

## 🧠 Project Objectives
1. Understand branch and geographical performance.
2. Identify the most profitable customer segments.
3. Analyze product line contributions and underperformance.
4. Detect temporal trends and revenue volatility.
5. Derive actionable business recommendations from correlations.

---

## 📊 Dataset Summary
- **Source:** Supermarket sales transactional dataset (adapted for demonstration)
- **Period Covered:** 3 months of operations
- **Fields Include:**  
  - Branch / City  
  - Customer Type (Member / Normal)  
  - Gender  
  - Product Line  
  - Unit Price, Quantity, Total, Tax (5%), Gross Income  
  - Date, Time, Payment Type, Customer Rating  

---

## ⚙️ Tools & Technologies
| Category | Tools Used |
|-----------|-------------|
| Programming | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Visualization | Power BI to be updated son|
| Data Handling | Jupyter Notebook |
| Version Control | Git & GitHub |

---

## 📈 Key Insights

### 1️⃣ Branch Performance
- Revenue is evenly distributed across branches.
- **Giza** leads with ≈$5,265 total income and the highest mean transaction value ($16.05).  
- Indicates a **standardized, efficient operational model**.

### 2️⃣ Customer Segmentation
- **Member customers** generate 42% more revenue than Normal customers.  
- **Ratings** are not correlated to transaction value — satisfaction depends on service, not cost.

### 3️⃣ Product Line Analysis
- Top 3 revenue categories:  
  - 🥤 Food and Beverages ($2,674)  
  - 🎽 Sports and Travel ($2,625)  
  - 💻 Electronic Accessories ($2,588)  
- Underperformer: 💅 Health and Beauty ($2,343)

### 4️⃣ Revenue Volatility
- Significant monthly income swings:  
  - Peak in Month 9 (≈660), trough in Month 4 (≈380).  
- Indicates **instability and dependency on short-term factors**.

### 5️⃣ Correlation Highlights
- Strong positive correlation between **Quantity (0.71)** and **Unit Price (0.63)** with Gross Income.
- Multicollinearity confirms derived metrics consistency (Sales, Tax, COGS, Gross Income).

---

## 🚀 Strategic Recommendations
| Focus Area | Action Plan |
|-------------|-------------|
| **Membership Growth** | Replicate high-performing branch tactics (Giza) and target normal customers for conversion. |
| **Revenue Stability** | Investigate peak/trough months and implement predictive stock and promotion timing. |
| **Product Optimization** | Diagnose Health & Beauty lag — adjust pricing or bundle promotions. |
| **Transaction Efficiency** | Train staff in upselling and cross-selling to lift mean gross income. |

---

## 🇰🇪 Kenyan Retail Context
In Kenya’s supermarket sector, these findings have immediate relevance:
- **Naivas** can use loyalty data to boost repeat purchases and basket size.  
- **Mathai Supermarket** can increase per-customer revenue through targeted upselling.  
- Volatility aligns with **end-month salary cycles** and **festive spikes**, which can be forecasted with data-driven planning.

---

## 📂 Repository Structure
```bash
Supermarket-Sales-Analysis/
│
├── data/
│   └── supermarket_sales.csv
│
├── notebooks/
│   └── supermarket_analysis.ipynb
│
├── visuals/
│   ├── monthly_volatility.png
│   ├── product_performance.png
│   └── membership_comparison.png
│
├── README.md
└── requirements.txt


---

📦 Installation & Usage

1. Clone this repository:

git clone https://github.com/yourusername/supermarket-sales-analysis.git


2. Navigate to the folder:

cd supermarket-sales-analysis


3. Install dependencies:

pip install -r requirements.txt


4. Open the notebook:

jupyter notebook notebooks/supermarket_analysis.ipynb




---

🧾 Requirements

Create a requirements.txt file with:

pandas
numpy
matplotlib
seaborn
jupyter


---

🧩 Future Work

Add predictive modeling for sales forecasting.

Integrate customer segmentation clustering.

Deploy interactive Power BI dashboard.

Extend analysis to other retail sectors in Kenya.



---

✍️ Author

John Muritu
Data Analyst | Business Intelligence Enthusiast | Kenya
📧 [johnmuritu22@gmail.com]
🔗 https://www.linkedin.com/in/ndungu-muritu-73768028a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app | GitHub


---

🏁 License

This project is open source and available under the MIT License.

