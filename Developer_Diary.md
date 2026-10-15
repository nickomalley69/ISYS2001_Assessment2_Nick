Step 1: understanding the problem/ problem statement
The goal of my tool was to help users track their spending. It does this by reading a CSV file of transactions, categorising each transaction, and storing the totals in a dictionary. Once the spending is grouped, the tool sends the summary to Gemini, which then gives personalised financial advice based on the user’s spending habits. The idea was to build a simple finance assistant that combines basic Python logic with an AI model.

Step 2: Inputs & Outputs
inputs - date, description, category, amount (of dollars)
outputs - a dictionary of category totals and personalized financial advice from google gemini based off the spending data.

Step 3: Logic in Plain English
The tool loads the CSV file and loops through each transaction. It checks the category and adds the amount to that category’s total inside a dictionary. After all transactions are processed, the dictionary shows how much was spent in each category. The tool then sends this dictionary to Gemini, which analyses the spending and returns personalised advice. Finally, the tool prints the summary and the advice for the user.

Step 4: Pseudocode
Start
Load CSV file
Create empty dictionary for category totals

For each transaction:
    Read category and amount
    If category not in dictionary:
        Add category with amount
    Else:
        Add amount to existing total

Send dictionary to Gemini
Receive personalised advice

Print category totals
Print advice
End

Step 5: Python Code
I wrote the logic in plain English first. Then I used AI assistance to help convert the pseudocode into Python code. The AI helped with reading CSV files, building the dictionary, and formatting the output. I also used AI to help integrate Gemini so the tool could generate personalised financial advice. I checked the code myself and made small changes to make sure it matched the assignment requirements.

Step 6: Testing
I tested the tool using sample CSV data. The category totals were correct, and Gemini returned advice that matched the spending patterns. I had to fix a couple of issues, like I fixed a small bug where transactions without a category caused a KeyError by adding a simple check before using the category. Overall, the tool works as intended. Planning the logic first made it easier to understand what the program needed to do, and using AI helped speed up the coding process.
