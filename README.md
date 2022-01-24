# Expense Management System

---

With this app user can track his/her expense of a month

## Features

---

- ### Basic user Authentication System
  - User will able to sign up
  - Can reset password
- ### Month wise expense
  - User will Add his/her total estimate budget and then can devide the budget in different categories like:
    Travel, House rent, Food etc
- ### Manage the expense

  - On each expense user need to add the expense.
  - Backend will deduct the amount of expense from the subcategory and from the total Budget.
  - There will be alert system to let the user know about his/her expense
  - There will be a progress bar for each category and the total budget.

- ### Progressbar based on expense

  | Available Budget Pecentage | Progress Bar                                        |
  | -------------------------- | --------------------------------------------------- |
  | >=80%                      | ![Progress](https://progress-bar.dev/80/?width=200) |
  | <80% && >= 50%             | ![Progress](https://progress-bar.dev/60/?width=200) |
  | <50% && >= 20%             | ![Progress](https://progress-bar.dev/30/?width=200) |
  | <20%                       | ![Progress](https://progress-bar.dev/10/?width=200) |

- ### Alert

  - If more than 80% of total budget in a Category or in Total Budged is comsumed then there will be an alert

- ### Summary

  - At the end of the month there will be a summary based on all expense.

  #### Example:

  | Category   | Budget | Expense | Savings |
  | ---------- | ------ | ------- | ------- |
  | House Rent | 20000  | 20000   | 0       |
  | Food       | 6000   | 5500    | +500    |
  | Travel     | 2000   | 2200    | -200    |

  | Total Budget | Expense | Savings |
  | ------------ | ------- | ------- |
  | 28000        | 27700   | +300    |
