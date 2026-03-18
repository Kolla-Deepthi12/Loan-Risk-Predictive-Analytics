📊 Loan Risk & Predictive Analytics in Lending

🚀 Fintech-focused analytics project aimed at identifying hidden risk in loan approvals and improving decision-making using data-driven insights with Excel, Python, and Power BI.

📌 Problem Statement

High loan approval rates are often considered a success metric.
However, they can mask underlying financial risk.

The real question is not just:
👉 Who gets approved?

But:
👉 Are we approving the right applicants while controlling risk?

🎯 Objective

-> Identify high-risk applicants early

-> Analyze financial behavior patterns

-> Combine risk analysis with predictive insights

-> Minimize expected financial loss

🛠️ Tools & Technologies

-> Excel → Data Cleaning

-> Python (Pandas, Matplotlib) → EDA & Feature Engineering

-> Power BI → Dashboard & Business Insights

🔧 Data Preparation

-> Handled missing values

-> Cleaned and structured dataset

-> Prepared data for analysis

🔍 Exploratory Data Analysis & Feature Engineering (Python)

-> Analyzed patterns in income, loan amount, and credit history

-> Performed distribution analysis and handled outliers

-> Built financial and risk-based features

📊 Engineered Features

- Total Income = Applicant + Co-applicant income

- Income-to-Loan Ratio → measures repayment capacity

- Risk Score → derived using financial indicators

⚠️ Risk Segmentation

-> Risk Category (High / Medium / Low)

-> Converts numerical scores into decision-friendly groups

💸 Financial Impact Metrics

- Expected Loss → potential loss from risky applicants

- Expected Profit → estimated return from approved loans

- Expected Interest → projected earnings from lending

👉 These features enabled:

-> Better risk understanding

-> Improved decision-making insights

🤖 Predictive Analysis (Rule-Based Approach)

-> Developed a rule-based prediction system using Risk Score and Risk Category

-> Simulated loan approval decisions based on financial risk

🔹 Prediction Logic

High Risk → Higher probability of rejection

Medium Risk → Conditional approval

Low Risk → Higher probability of approval

Compared predicted outcomes with actual loan status

Observed strong alignment between risk segmentation and approval behavior

👉 This approach reflects how real-world lending decisions are often made using risk rules before advanced ML models.

📊 Dashboard Overview (Power BI)
🔹 Key KPIs

👥 Total Applicants: 598

✅ Approval Rate: 69%

⚠️ High Risk Applicants: 7%

💸 Expected Loss: 3.42K

🔹 Risk Analysis

Risk Category Distribution

Risk Score Distribution

Credit History Impact

Income vs Loan Analysis

Profit vs Loss

🔹 Prediction Analysis

Actual vs Predicted Approval

Prediction vs Risk Category

📈 Key Insights

-> Risk is not evenly distributed — a small segment drives most expected loss

-> Credit history has a stronger influence than income

-> High income does not always indicate low risk

-> Low income + high loan → higher default probability

-> Prediction aligns with risk segmentation, validating decision logic

💡 Business Takeaways

-> Approval rate alone is not a reliable success metric

-> Risk segmentation improves decision quality

-> Credit behavior should be prioritized in lending decisions

-> Monitoring high-risk segments can significantly reduce losses

📌 Conclusion

This project highlights that:

Effective lending decisions require both
risk understanding + predictive insight

By combining both, organizations can move from
reactive approvals → proactive risk management
