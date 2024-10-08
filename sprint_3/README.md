## Project 3: Plan Profitability Analysis

### Objective
This project focuses on analyzing the profitability of two prepaid plans offered by the telecom operator Megaline: **Surf** and **Ultimate**. The company aims to determine which plan brings in more revenue to adjust the advertising budget accordingly.

### What Was Done
- Collected and prepared data from 500 Megaline clients, including information about calls, messages, and internet usage.
- Calculated the monthly revenue for each client by accounting for the fixed plan costs and extra charges for minutes, messages, and data exceeding the plan limits.
- Conducted statistical analysis to compare the profitability of the two plans:
  - Described customer behavior in terms of minutes used, text messages sent, and data consumed.
  - Performed hypothesis testing to check if:
    - The average revenue differs between users of the **Surf** and **Ultimate** plans.
    - The average revenue in the NY-NJ area differs from other regions.

### Results
- The analysis revealed that:
  - Users of the **Ultimate** plan typically generate more revenue than those on the **Surf** plan due to the higher monthly charge.
  - There was a statistically significant difference in the average revenue between the two plans.
  - The average revenue from users in the NY-NJ area did not significantly differ from users in other regions.

### Hypothesis Testing
- **Null Hypothesis**: The average revenue from **Ultimate** plan users is the same as from **Surf** plan users.
- **Alternative Hypothesis**: The average revenue from **Ultimate** plan users is different from **Surf** plan users.
- **Test Method**: T-test was used to compare the means of the two groups.

### Notebook
- [Notebook](./plan_profitability.ipynb)

### Conclusion
This project provided valuable insights into the revenue generated by the two prepaid plans offered by Megaline. The analysis concluded that the **Ultimate** plan, with its higher monthly charge and lower rates for overage usage, typically yields more revenue compared to the **Surf** plan. This information will help the company make informed decisions on how to allocate advertising resources.
