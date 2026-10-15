# ISYS2001_Assessment2_Nick
Assessment 2 - Finance Spending Summary Assistant

This assistant helps users track their spending by reading a CSV file of transactions, categorising each transaction, and storing the totals in a dictionary. It then sends the spending summary to Gemini, which analyses the data and gives personalised financial advice based on the user’s habits.

sample input:
Date,Description,Category,Amount
2024-01-01,Coffee,Food,5.50
2024-01-02,Petrol,Transport,40.00
2024-01-03,Groceries,Food,32.10
2024-01-04,Netflix,Entertainment,15.99

sample output:
Total spending: $93.59

Category totals:
Food: $37.60
Transport: $40.00
Entertainment: $15.99

Highest spending category: Transport
Lowest spending category: Entertainment

Gemini Advice:
"You're spending a lot on Transport this week. Consider planning trips or carpooling to reduce costs."
