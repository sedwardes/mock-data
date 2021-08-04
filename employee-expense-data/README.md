## Case Study

ABC is one of the largest universities in North America. Due to its rapid growth of students and staff population, the expense reimbursement data is also growing exponentially. The board members are interested to know if there is any misconduct in the expense reimbursement process or potential risks, control failures etc.

You are the data scientist of the University’s Internal Audit division and you would like to create a dashboard to continuously monitor expense reimbursement data and find insights by cross checking the employee data from HR department. 
Please cleanse [Expense data] and [Employee table], develop a data model and create a visualization that supports your analysis. The following are some testing hypotheses you can use as reference:

- Are expenses evenly distributed over time?
- What are the top expense types?
- Are expenses approved by employees direct managers?

## Tools

The following Colab notebooks have been pre-populated with the case study and starter code:

- Case study - Python starter code: https://colab.research.google.com/drive/1xkh6F6R2Ph_38WZxWsfgqx26VUIyi0yg?usp=sharing
- Case study - R starter code: https://colab.research.google.com/drive/1mZhfD89vyni0qlS4-ku6ncTvQYakt9KI?usp=sharing

## Starter code

**Python**

```python
import pandas as pd

employees_data_path = "https://github.com/sedwardes/mock-data/raw/main/employee-expense-data/Employee%20table.csv"
employees = pd.read_csv(employees_data_path)
employees.head()

expenses_data_path = "https://github.com/sedwardes/mock-data/raw/main/employee-expense-data/Expense%20data.csv"
expenses = pd.read_csv(expenses_data_path)
expenses.head()
```

**R**

```r
employees_data_path <- "https://github.com/sedwardes/mock-data/raw/main/employee-expense-data/Employee%20table.csv"
employees <- readr::read_csv(employees_data_path)
head(employees)

expenses_data_path <- "https://github.com/sedwardes/mock-data/raw/main/employee-expense-data/Expense%20data.csv"
expenses <- readr::read_csv(expenses_data_path)
head(expenses)
```

