SpendDNA — Personal Finance & Behavioral Spend Analytics

SpendDNA is an end-to-end data analytics and behavioral modeling pipeline designed to transform raw, unstructured bank transaction exports into actionable financial insights, spending archetypes, and anomaly detection reports.

Overview

Modern transaction statements are often cluttered with obscure merchant codes, inconsistent date formatting, and mixed transaction types. SpendDNA standardizes this data, maps transactions to canonical merchants and spending categories, and runs behavioral heuristics to uncover habit loops, temporal spikes, and financial risk indicators.

Key Features

- Transaction Parser & CleanerMulti-format datetime parsing and duplicate record elimination.   Currency cleaning (removing ₹, Rs., commas) and transaction type normalization (Debit/DR $\rightarrow$ debit, Credit/CR $\rightarrow$ credit).
- Entity Extraction & Category TaggingRule-based canonical vendor extraction from messy bank narration strings (e.g., matching UPI IDs, ATM withdrawals, and corporate parent names).   Hierarchical categorization across standard expenditure buckets: Food Delivery, Quick Commerce, E-commerce, Utilities, Investments, Fuel, and Transport.
- Temporal & Circadian Rhythm AnalysisDay-of-week spending distribution (Weekday vs. Weekend outflow comparisons):    24-hour transaction frequency heatmapping.   Behavioral habit tracking: Late-night food ordering (21:00–02:00) and morning cafe runs (08:00–11:00).
- Statistical Anomaly Detection : Z-score calculation on category-level expenditure distributions ($Z > 2.0$) to flag unusual, high-ticket expenses.
- Financial Archetyping : Automatic behavioral persona tagging based on consumption proportions and savings performance (e.g., THE SHOPAHOLIC, THE YOLO SPENDER).

Analytics Summary (Demo Dataset)
Total Transactions - 1,310   
Unique Vendors - 41   
Total Inflow (Credits) - ₹5,09,774.00   
Total Outflow (Debits) - ₹16,78,901.00   
Net Financial Deficit-₹11,69,127.00   
Savings Rate-229.34%   
Top Spending CategoryE-commerce - (38.45% of consumption spend)   
Top Merchant by OutflowAmazon - (₹3,28,530.00 across 86 transactions)   
Flagged Anomalies - ($Z > 2.0$)38 transactions  

Behavioral Archetypes IdentifiedTHE SHOPAHOLIC: Triggered when E-commerce debits exceed 15% of total outflow (Observed: 35.97% of debits / 38.45% of consumption).   THE YOLO SPENDER: Triggered when the net savings rate falls below 10% (Observed: -229.34%).   Late-Night Snacking: 21.22% of all food delivery transactions occur between 21:00 and 02:00.   Morning Coffee Habit: 34.44% of cafe purchases occur between 08:00 and 11:00. 
