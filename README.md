# PhonePe-Transaction-Performance-Dashboard-By-Aditya-Kalyan-
This project analyzes transaction performance and customer behavior using a Power BI dashboard inspired by a fintech ecosystem like PhonePe.  The goal is to transform raw transaction data into meaningful KPIs and business insights.

# 🚀 Project Overview

The dashboard is divided into two analytical sections:

# 1️⃣ Transaction Performance Dashboard

Total Transactions: 297K+
Total Revenue: 3.43 BN
Success Rate: 0.96
Monthly Transaction Trends
Revenue by Service (Loans, Insurance, Money Transfer, Recharge Bills)
Payment Status Analysis

# 2️⃣ Customer & Payment Behavior Analysis

Total Premium: 512.92M
Total Customers: 108K
Age Group Analysis
Insurance Type Premium Breakdown
Customer Growth Trend
Monthly Premium Analysis

# 📌 Business Problems Solved

✔ Identify revenue-driving services
✔ Monitor transaction success rate
✔ Analyze payment failures
✔ Segment high-value customers
✔ Track growth trends

# 🛠 Tools & Technologies Used

Power BI
DAX (Data Analysis Expressions)
Data Modeling (Star Schema)
KPI Design
Interactive Slicers

# 📈 Key DAX Measures

# Total Transactions
Total Transactions = COUNT(All_Transactions[Transaction_ID]) 

# Total Revenue
Total Revenue = SUM(All_Transactions[Amount])

# Success Rate
Success Rate =
DIVIDE(
    CALCULATE(COUNT(All_Transactions[Transaction_ID]),
    All_Transactions[Payment_Status] = "Successful"),
    [Total Transactions]
)

# Average Order Value
AOV = DIVIDE([Total Revenue], [Total Transactions])

# 📊 Data Model

The model follows a relational structure connecting:
Insurance
Loans
Recharge Bills
Money Transfer
All Transactions
Users Table
Ensuring clean relationships and optimized DAX performance.

# 🎯 Key Learnings :
KPI storytelling matters more than visuals
Clean data modeling improves performance
DAX measures drive dynamic insights
Dashboard UI impacts user experience

# 📸 Dashboard Preview :

# Customer & Payment Behavior Analysis 

<img width="1416" height="851" alt="Customer   Payment Behavior Analysis Dashboard" src="https://github.com/user-attachments/assets/846737f0-7665-42d3-82f5-0e401274f4dc" /> 

# Phone Pe Transaction Performance Dashboard 

<img width="1434" height="852" alt="Phone Pe Transaction Performance Dashboard" src="https://github.com/user-attachments/assets/71594d05-6b12-43c5-8e87-ebe0e206dac4" />



# 👨‍💻 About Me : 
Aditya Kalyan
Data Analytics Mentor | Founder – Data Detective Club

I help students master Power BI, DAX, SQL & build real-world analytics projects.

# 🔗 Connect With Me

LinkedIn: [(Add your LinkedIn profile link here)](https://www.linkedin.com/in/adityaakalyan/) 
Data Detective Club LinkedIn : https://www.linkedin.com/company/data-detective-club/?viewAsMember=true  


# Thanks for Visiting !! 



