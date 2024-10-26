#### Date-Data-Analysis

![Date Data](https://github.com/user-attachments/assets/d0ab59ec-5f2c-43ae-b6f6-590d6ac06499)


## Objective:

Analyze project timelines to calculate the duration from the start date to the current date and assess the status based on the age of the project.

## Problems Solved and Approach:

- Calculating Years, Months, and Days Used from Start Date to Today

  Objective: Determine the project duration from its start date to today in years, months, and days.

Method:
Years used:
=DATEDIF(B2, TODAY(), "Y")

Months used:
=DATEDIF(B2, TODAY(), "YM")

Days used:
=DATEDIF(B2, TODAY(), "MD")

- Determining Project Status Based on Age

Objective: Assign status as "Old" if the project age exceeds 20 years; otherwise, mark it as "Active."

Method:
Used the IF formula:
=IF(YEARFRAC(B2, TODAY()) > 20, "Old", "Active")
Applied Conditional Formatting to format all "Old" statuses with a red font color using the formula:
=B7="Old"


## Summary of Key Insights:
Calculating the precise years, months, and days helped assess the timeline for each project.

The status categorization (Old/Active) based on project age provided insights into which projects may require re-evaluation or updates.

Formatting the "Old" status in red ensured quick identification of long-standing projects.


## Conclusion:

The project highlighted the significance of leveraging Excel formulas for effective data analysis. Using tools such as DATEDIF, IF logic, and conditional formatting improved the clarity and usability of the timeline data. These techniques enabled precise tracking of project durations, quick classification of statuses, and easy identification of long-running projects.

The attached pictures provide visual representation and further validation of the data and analysis carried out.

